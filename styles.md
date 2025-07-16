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
    width: 100vw;
    height: 100vh;
    padding: 20px;
    box-sizing: border-box;
    background-color: #f5f7fa;
    background-image: linear-gradient(135deg, #f5f7fa 0%, #e4e8ed 100%);
    font-family: 'Segoe UI', 'Roboto', 'Helvetica Neue', sans-serif;
    position: absolute;
    top: 0;
    left: 0;
    overflow: auto;
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
    border-bottom: 3px solid var(--primary);
    padding-bottom: 10px;
    text-align: center;
  }

  h2 {
    color: var(--primary);
    font-size: 1.8em;
    margin-top: 0.5em;
  }

  /* ===== TEXTO E PARÁGRAFOS ===== */
  p {
    font-size: 1em;
    line-height: 1.6;
    margin-bottom: 1em;
  }

  /* ===== LISTAS ===== */
  ul, ol {
    font-size: 1em;
    padding-left: 1.2em;
  }

  li {
    margin-bottom: 0.5em;
  }

  /* ===== TABELAS ===== */
  table {
    width: 100%;
    font-size: 0.9em;
  }

  /* ===== IMAGENS ===== */
  img {
    max-height: 40vh;
    max-width: 100%;
    object-fit: contain;
  }

  /* ===== GRIDS ===== */
  .grid-container {
    display: grid;
    gap: 15px;
    height: 70vh;
  }

  /* ===== CÓDIGO ===== */
  pre {
    font-size: 0.8em;
    max-height: 50vh;
    overflow: auto;
  }
</style>

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>