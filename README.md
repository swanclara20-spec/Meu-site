<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Loja Vintage de Doces</title>
<style>
  body {
    background-color: #E5D7C4; /* Bone */
    font-family: 'Georgia', serif;
    color: #4C3D19; /* Café Noir */
    margin: 0;
    padding: 0;
  }

  header {
    background-color: #354024; /* Kombu Green */
    padding: 20px;
    text-align: center;
    position: relative;
  }

  /* Logo minimalista de cisne */
  .logo {
    display: inline-flex;
    align-items: center;
    font-size: 2em;
    font-weight: bold;
    color: #CFBB99; /* Tan */
    cursor: default;
  }

  .logo svg {
    width: 40px;
    height: 40px;
    fill: #CFBB99;
    margin-right: 10px;
  }

  nav {
    margin-top: 10px;
  }

  nav a {
    color: #CFBB99;
    text-decoration: none;
    margin: 0 15px;
    transition: color 0.3s ease;
  }

  nav a:hover {
    color: #889063; /* Moss Green */
  }

  main {
    padding: 30px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
  }

  .produto {
    background-color: #CFBB99; /* Tan */
    border-radius: 12px;
    box-shadow: 3px 3px 6px rgba(0,0,0,0.2);
    padding: 15px;
    text-align: center;
    transition: transform 0.3s ease;
    cursor: pointer;
  }

  .produto:hover {
    transform: scale(1.05);
  }

  .produto img {
    max-width: 100%;
    border-radius: 10px;
  }

  .produto h3 {
    margin: 12px 0 8px 0;
    font-family: 'Georgia', serif;
  }

  .icone-interativo {
    display: inline-block;
    margin-top: 10px;
    font-size: 1.5em;
    color: #354024;
    transition: color 0.3s ease;
    cursor: pointer;
  }

  .icone-interativo:hover {
    color: #889063;
  }

  footer {
    background-color: #4C3D19; /* Café Noir */
    color: #CFBB99;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
  }
</style>
</head>

<body>
  <header>
    <div class="logo">
      <!-- Logo minimalista de Cisne como SVG -->
      <svg viewBox="0 0 64 64" aria-hidden="true" focusable="false">
        <path d="M32 3c-8 8-8 19-4 23-8-3-12 8-7 12 0-12 8-21 11-21 8 5 11 10 11 12 0-9-4-17-11-26z" />
      </svg>
      Cisne Doce Vintage
    </div>
    <nav>
      <a href="#produtos">Produtos</a>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <main id="produtos">
    <div class="produto" tabindex="0">
      <img src="https://via.placeholder.com/250?text=Brigadeiro" alt="Brigadeiro" />
      <h3>Brigadeiros</h3>
      <div class="icone-interativo" title="Adicionar aos favoritos" role="button" tabindex="0">&#10084;</div>
    </div>
    <div class="produto" tabindex="0">
      <img src="https://via.placeholder.com/250?text=Beijinho" alt="Beijinho" />
      <h3>Bolos</h3>
      <div class="icone-interativo" title="Adicionar aos favoritos" role="button" tabindex="0">&#10084;</div>
    </div>
    <div class="produto" tabindex="0">
      <img src="https://via.placeholder.com/250?text=Quindim" alt="Quindim" />
      <h3>Variados</h3>
      <div class="icone-interativo" title="Adicionar aos favoritos" role="button" tabindex="0">&#10084;</div>
    </div>
  </main>

  <section id="sobre" style="padding: 30px; background-color: #889063; color: #4C3D19;">
    <h2>Sobre Nós</h2>
    <p>Na Asas de açúcar, trazemos os sabores clássicos dos doces brasileiros com um toque de elegância vintage para aquecer seu coração.</p>
  </section>

  <section id="contato" style="padding: 30px; background-color: #CFBB99; color: #4C3D19;">
    <h2>Contato</h2>
    <p>Email: contato@cisnedoce.com.br</p>
    <p>Telefone: (11) 1234-5678</p>
  </section>

  <footer>
    &copy; 2024 Asas de açúcar - Todos os direitos reservados
  </footer>

</body>
</html>
