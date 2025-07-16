<style>
  /* ===== ESTILOS OTIMIZADOS ===== */
  :root {
    --primary: #3498db;
    --secondary: #2c3e50;
    --accent: #e74c3c;
    --light-bg: #f8f9fa;
  }

  /* LAYOUT ULTRA-COMPACTO */
  section {
    width: 100vw;
    height: 100vh;
    padding: 5px 10px 0 10px; /* Top reduzido */
    margin: 0;
    background: #f5f7fa;
    font-family: 'Segoe UI', system-ui, sans-serif;
    overflow: hidden;
    display: flex;
    flex-direction: column;
  }

  /* CABEÇALHOS COMPACTOS */
  h1 {
    color: var(--secondary);
    font-size: 1.8em; /* 28% menor */
    margin: 2px 0 5px 0; /* Margens mínimas */
    padding-bottom: 3px;
    border-bottom: 1px solid var(--primary);
  }

  h2 {
    font-size: 1.5em; /* 17% menor */
    margin: 3px 0;
  }

  h3 {
    font-size: 1.2em;
    margin: 2px 0;
  }

  h4 {
    font-size: 1em;
    margin: 1px 0;
  }

  /* ELEMENTOS DE TEXTO COMPRIMIDOS */
  p {
    font-size: 0.85em;
    line-height: 1.3;
    margin: 3px 0;
  }

  /* LISTAS SUPER COMPACTAS */
  ul, ol {
    font-size: 0.8em;
    padding-left: 15px;
    margin: 5px 0;
  }

  li {
    margin-bottom: 2px;
    padding: 1px 0;
  }

  /* IMAGENS ULTRA-COMPACTAS */
  img {
    max-height: 28vh; /* Redução adicional de 20% */
    max-width: 65%;
    margin: 2px auto;
    object-fit: contain;
  }

  /* TABELAS COMPACTAS */
  table {
    font-size: 0.75em;
    margin: 3px 0;
  }

  th, td {
    padding: 2px 5px;
  }

  /* GRIDS OTIMIZADOS */
  .grid-container {
    gap: 4px;
    margin: 0;
    padding: 0;
  }

  /* BLOCO DE CÓDIGO MAIS APERTO */
  pre {
    font-size: 0.65em;
    max-height: 35vh;
    margin: 3px 0;
    padding: 5px;
  }

  /* CONTÊINERES DE CONTEÚDO */
  .content-wrapper {
    max-height: calc(100vh - 30px);
    overflow-y: auto;
  }
</style>

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
