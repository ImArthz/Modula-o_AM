<style>
  :root {
    --primary: #3498db;
    --secondary: #2c3e50;
    --accent: #e74c3c;
    --light-bg: #f8f9fa;
    --dark-bg: #343a40;
    --text: #212529;
    --text-light: #f8f9fa;
  }

  /* RESET BASE */
  * {
    box-sizing: border-box;
  }

  html, body {
    margin: 0;
    padding: 0;
  }

  section {
    width: 100vw;
    height: 100vh;
    padding: 2rem 3rem;
    margin: 0 auto;
    background-color: #f5f7fa;
    background-image: linear-gradient(135deg, #f5f7fa 0%, #e4e8ed 100%);
    font-family: 'Segoe UI', 'Roboto', 'Helvetica Neue', sans-serif;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    overflow-y: auto;
  }

  .content-wrapper {
    max-width: 1200px;
    width: 100%;
    margin-top: 2rem;
  }

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

  p {
    font-size: 0.95em;
    line-height: 1.5;
    margin-bottom: 0.8em;
  }

  ul, ol {
    font-size: 0.9em;
    padding-left: 1.2em;
  }

  li {
    margin-bottom: 0.4em;
  }

  table {
    width: 100%;
    font-size: 0.85em;
  }

  img {
    max-height: 35vh;
    max-width: 70%;
    object-fit: contain;
  }

  .grid-container {
    display: grid;
    gap: 6px;
    height: auto;
  }

  pre {
    font-size: 0.75em;
    max-height: 40vh;
    overflow: auto;
  }
</style>


<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

