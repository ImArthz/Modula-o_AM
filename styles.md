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

  /* ===== FUNDO E TIPOGRAFIA ===== */
  section {
    background-color: #f5f7fa;
    background-image: linear-gradient(135deg, #f5f7fa 0%, #e4e8ed 100%);
    font-family: 'Segoe UI', 'Roboto', 'Helvetica Neue', sans-serif;
    color: var(--text);
    padding: 60px;
  }

  /* ===== CABEÇALHOS ===== */
  h1 {
    color: var(--secondary);
    font-size: 2.8em;
    font-weight: 700;
    margin-bottom: 0.5em;
    border-bottom: 3px solid var(--primary);
    padding-bottom: 15px;
    text-align: center;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
  }

  h2 {
    color: var(--primary);
    font-size: 2.2em;
    border-left: 5px solid var(--primary);
    padding-left: 15px;
    margin-top: 1.5em;
  }

  h3 {
    color: var(--secondary);
    font-size: 1.8em;
    margin-top: 1em;
  }

  /* ===== TEXTO E PARÁGRAFOS ===== */
  p {
    font-size: 1.2em;
    line-height: 1.6;
    margin-bottom: 1em;
  }

  strong {
    color: var(--accent);
    font-weight: 600;
  }

  a {
    color: var(--primary);
    text-decoration: none;
    transition: all 0.3s ease;
  }

  a:hover {
    color: var(--accent);
    text-decoration: underline;
  }

  /* ===== LISTAS ===== */
  ul, ol {
    font-size: 1.2em;
    margin-left: 1.5em;
    line-height: 1.6;
  }

  li {
    margin-bottom: 0.8em;
    position: relative;
  }

  ul li::before {
    content: "•";
    color: var(--primary);
    font-weight: bold;
    display: inline-block;
    width: 1em;
    margin-left: -1em;
  }

  /* ===== TABELAS ===== */
  table {
    width: 100%;
    border-collapse: collapse;
    margin: 2em 0;
    box-shadow: 0 2px 3px rgba(0,0,0,0.1);
  }

  th {
    background-color: var(--primary);
    color: white;
    padding: 12px;
    text-align: left;
    font-weight: 600;
  }

  td {
    padding: 12px;
    border-bottom: 1px solid #ddd;
  }

  tr:nth-child(even) {
    background-color: rgba(52, 152, 219, 0.05);
  }

  tr:hover {
    background-color: rgba(52, 152, 219, 0.1);
  }

  /* ===== BLOCOS DE CÓDIGO ===== */
  pre {
    background-color: var(--secondary);
    color: #f8f8f2;
    padding: 1em;
    border-radius: 5px;
    overflow-x: auto;
    font-family: 'Fira Code', 'Consolas', monospace;
    font-size: 0.9em;
    line-height: 1.5;
    margin: 1.5em 0;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }

  code {
    font-family: 'Fira Code', 'Consolas', monospace;
    background-color: rgba(52, 152, 219, 0.1);
    padding: 0.2em 0.4em;
    border-radius: 3px;
    font-size: 0.9em;
  }

  /* ===== IMAGENS ===== */
  img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 1.5em auto;
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }

  img[alt="centered"] {
    display: block;
    margin: 0 auto;
  }

  img[alt="small"] {
    width: 40%;
  }

  img[alt="medium"] {
    width: 65%;
  }

  img[alt="large"] {
    width: 85%;
  }

  /* ===== CLASSES UTILITÁRIAS ===== */
  .transparent {
    background-color: transparent !important;
  }

  .text-center {
    text-align: center !important;
  }

  .text-right {
    text-align: right !important;
  }

  .text-left {
    text-align: left !important;
  }

  .text-primary {
    color: var(--primary) !important;
  }

  .text-secondary {
    color: var(--secondary) !important;
  }

  .text-accent {
    color: var(--accent) !important;
  }

  .bg-primary {
    background-color: var(--primary) !important;
    color: white !important;
  }

  .bg-secondary {
    background-color: var(--secondary) !important;
    color: white !important;
  }

  .bg-accent {
    background-color: var(--accent) !important;
    color: white !important;
  }

  .shadow {
    box-shadow: 0 4px 6px rgba(0,0,0,0.1) !important;
  }

  .rounded {
    border-radius: 5px !important;
  }

  /* ===== LAYOUTS DE GRADE ===== */
  .grid {
    display: grid;
    gap: 2em;
    margin: 2em 0;
  }

  .grid-2 {
    grid-template-columns: repeat(2, 1fr);
  }

  .grid-3 {
    grid-template-columns: repeat(3, 1fr);
  }

  .grid-4 {
    grid-template-columns: repeat(4, 1fr);
  }

  .grid-item {
    background-color: white;
    padding: 1.5em;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  }

  /* ===== ANIMAÇÕES ===== */
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .animate {
    animation: fadeIn 0.6s ease-out forwards;
  }

  /* ===== COMPONENTES ESPECÍFICOS PARA TELECOM ===== */
  .signal-diagram {
    background-color: white;
    padding: 2em;
    border-radius: 8px;
    border: 1px solid #ddd;
  }

  .modulation-formula {
    font-size: 1.5em;
    text-align: center;
    padding: 1em;
    background-color: rgba(52, 152, 219, 0.1);
    border-radius: 5px;
    margin: 1em 0;
  }

  .frequency-spectrum {
    width: 100%;
    height: 300px;
    background: linear-gradient(90deg, #3498db, #e74c3c);
    position: relative;
    border-radius: 5px;
    overflow: hidden;
  }

  /* ===== RESPONSIVIDADE ===== */
  @media (max-width: 768px) {
    section {
      padding: 30px;
    }
    
    h1 {
      font-size: 2em;
    }
    
    .grid-2, .grid-3, .grid-4 {
      grid-template-columns: 1fr;
    }
  }
</style>

<!-- MathJax Configuration -->
<script>
  MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']]
    },
    svg: {
      fontCache: 'global'
    }
  };
</script>

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<!-- Font Awesome Icons -->
<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
