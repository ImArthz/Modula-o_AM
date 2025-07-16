<style>
  /* ===== ESTILOS GERAIS ===== */
  :root {
    --primary: #3498db;
    --secondary: #2c3e50;
    --accent: #e74c3c;
    --light-bg: #f8f9fa;
    --dark-bg: #343a40;
    --text: #212529;
    --text-light: #f8f9fa;
  }

  /* AJUSTES PRINCIPAIS PARA TELA CHEIA */
  section {
    width: 90vw;
    height: 90vh;
    padding: 15px;
    box-sizing: border-box;
    background-color: #f5f7fa;
    background-image: linear-gradient(135deg, #f5f7fa 0%, #e4e8ed 100%);
    font-family: 'Segoe UI', 'Roboto', 'Helvetica Neue', sans-serif;
    position: absolute;
    top: 0;
    left: 0;
    overflow: hidden; /* Evita rolagem na seção principal */
  }

  .content-wrapper {
    max-height: calc(100vh - 80px);
    overflow-y: auto;
  }

  /* ===== CABEÇALHOS ===== */
  h1 {
    color: var(--secondary);
    font-size: 2.5em;
    margin-top: 0;
    border-bottom: 2px solid var(--primary);
    padding-bottom: 6px;
    text-align: center;
  }

  h2 {
    color: var(--primary);
    font-size: 1.8em;
    margin-top: 0.5em;
  }

  /* ===== TEXTO E PARÁGRAFOS ===== */
  p {
    font-size: 0.95em;
    line-height: 1.5;
    margin-bottom: 0.8em;
  }

  /* ===== LISTAS ===== */
  ul, ol {
    font-size: 0.9em;
    padding-left: 1.2em;
  }

  li {
    margin-bottom: 0.4em;
  }

  /* ===== TABELAS ===== */
  table {
    width: 100%;
    font-size: 0.85em;
  }

  /* ===== IMAGENS ===== */
  img {
    max-height: 35vh; /* Reduzido para dar mais espaço */
    max-width: 70%;
    object-fit: contain;
  }

  /* ===== GRIDS ===== */
  .grid-container {
    display: grid;
    gap: 6px;
    height: auto; /* Removido altura fixa para evitar rolagem */
  }

  /* ===== CÓDIGO ===== */
  pre {
    font-size: 0.75em;
    max-height: 40vh; /* Reduzido para dar mais espaço */
    overflow: auto;
  }
</style>

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

