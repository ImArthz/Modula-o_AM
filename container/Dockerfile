FROM ubuntu:latest

# Instala dependências
RUN apt-get update && \
    apt-get install -y \
    python3 \
    nodejs \
    npm \
    python-is-python3 \
    git \
    wget

# Instala Marp CLI
RUN npm install -g @marp-team/marp-cli

# Configura o diretório de trabalho
WORKDIR /workspace

# Configura a porta de exposição
EXPOSE 8080

# Comando de inicialização
CMD ["marp", "--server", "--html", "--watch", ".", "--port", "8080", "--allow-local-files"]
