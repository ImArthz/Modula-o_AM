FROM ubuntu:latest

# Instala dependências
RUN apt-get update && \
    apt-get install -y \
    python3 \
    nodejs \
    npm \
    python-is-python3 \
    git \
    wget \
    unzip

# Instala Marp CLI e configurações globais
RUN npm install -g @marp-team/marp-cli && \
    mkdir -p /workspace/{styles,imgs,slides}

# Configura o diretório de trabalho
WORKDIR /workspace

# Copia os arquivos necessários (serão montados via volume)
COPY ./styles/styles.css /workspace/styles/
COPY ./imgs /workspace/imgs/
COPY ./slides /workspace/slides/

# Instala MathJax localmente (opcional)
RUN wget https://github.com/mathjax/MathJax/archive/refs/tags/3.2.0.zip && \
    unzip 3.2.0.zip -d /workspace/libs/ && \
    rm 3.2.0.zip

# Configura a porta de exposição
EXPOSE 8080

# Comando de inicialização
CMD ["marp", "--server", "--html", "--watch", "slides/", "--port", "8080", "--allow-local-files"]
