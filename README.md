# cocina-del-mare

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Cozinha do Mar: descubra receitas, curiosidades e dicas sobre frutos do mar.">
  <title>Cozinha do Mar | Sabores do Oceano</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f7f5ef;
      color: #173c43;
      line-height: 1.7;
    }

    header {
      background: #103b42;
      color: white;
      padding: 22px 7%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 15px;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
      letter-spacing: 1px;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 18px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 14px;
    }

    nav a:hover {
      color: #e6c99a;
    }

    .hero {
      min-height: 440px;
      padding: 90px 8%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      color: white;
      background:
        linear-gradient(rgba(9, 42, 48, .65), rgba(9, 42, 48, .7)),
        url("https://images.unsplash.com/photo-1515003197210-e0cd7184f8b5?auto=format&fit=crop&w=1800&q=85")
        center/cover;
    }

    .hero p {
      color: #e6c99a;
      text-transform: uppercase;
      letter-spacing: 3px;
      font-size: 12px;
      margin-bottom: 15px;
    }

    .hero h1 {
      font-family: Georgia, serif;
      font-size: clamp(38px, 7vw, 68px);
      line-height: 1.15;
      max-width: 700px;
      margin-bottom: 22px;
    }

    .hero .intro {
      max-width: 570px;
      color: #f1f1ed;
      font-size: 17px;
    }

    .botao {
      display: inline-block;
      background: #d6b77d;
      color: #173c43;
      padding: 12px 23px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 3px;
      margin-top: 25px;
      width: fit-content;
    }

    section {
      padding: 70px 8%;
      scroll-margin-top: 20px;
    }

    .subtitulo {
      color: #a47b3e;
      text-transform: uppercase;
      font-size: 12px;
      letter-spacing: 3px;
      margin-bottom: 10px;
    }

    h2 {
      font-family: Georgia, serif;
      font-size: clamp(29px, 4vw, 42px);
      line-height: 1.2;
      margin-bottom: 18px;
    }

    .descricao {
      max-width: 700px;
      color: #5b6b6c;
      margin-bottom: 35px;
    }

    .grade {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 25px;
    }

    .card {
      background: white;
      overflow: hidden;
      border-radius: 5px;
      box-shadow: 0 5px 22px rgba(20, 50, 50, .07);
    }

    .card a.imagem {
      display: block;
      overflow: hidden;
    }

    .card img {
      display: block;
      width: 100%;
      height: 230px;
      object-fit: cover;
      transition: transform .35s;
    }

    .card a.imagem:hover img {
      transform: scale(1.05);
    }

    .card-conteudo {
      padding: 23px;
    }

    .card h3 {
      font-family: Georgia, serif;
      font-size: 25px;
      margin-bottom: 10px;
    }

    .card p {
      color: #627174;
      font-size: 14px;
      margin-bottom: 15px;
    }

    .link {
      color: #a47b3e;
      font-weight: bold;
      text-decoration: none;
    }

    .faixa {
      background: #e9e4d7;
    }

    .artigo {
      max-width: 850px;
      margin: auto;
    }

    .artigo h2 {
      margin-bottom: 20px;
    }

    .artigo h3 {
      font-family: Georgia, serif;
      font-size: 24px;
      margin: 28px 0 8px;
    }

    .artigo p, .artigo li {
      color: #536769;
      margin-bottom: 12px;
    }

    .artigo ul, .artigo ol {
      padding-left: 23px;
    }

    .receita {
      background: white;
      padding: 25px;
      margin-top: 20px;
      border-left: 4px solid #d6b77d;
    }

    .contato {
      background: #103b42;
      color: white;
      text-align: center;
    }

    .contato p {
      color: #e1e8e5;
      max-width: 600px;
      margin: 0 auto 15px;
    }

    .contato .subtitulo {
      color: #e6c99a;
    }

    footer {
      background: #092d33;
      color: #dbe3df;
      text-align: center;
      padding: 25px 15px;
      font-size: 13px;
    }

    @media (max-width: 600px) {
      header {
        padding: 20px;
      }

      nav {
        gap: 12px;
      }

      .hero {
        min-height: 390px;
        padding: 65px 25px;
      }

      section {
        padding: 50px 22px;
      }

      .card img {
        height: 210px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">COZINHA DO MAR</div>
    <nav>
      <a href="#inicio">Início</a>
      <a href="#especialidades">Especialidades</a>
      <a href="#polvo">Polvo</a>
      <a href="#lagosta">Lagosta</a>
      <a href="#camarao">Camarão</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="inicio">
      <p>Gastronomia • Oceano • Experiências</p>
      <h1>O melhor do mar à sua mesa.</h1>
      <div class="intro">
        Explore os sabores dos frutos do mar, descubra ingredientes
        especiais e aprenda a preparar pratos que transformam
        qualquer refeição em uma experiência.
      </div>
      <a class="botao" href="#especialidades">Explorar sabores</a>
    </section>

    <section id="especialidades">
      <div class="subtitulo">Nossas especialidades</div>
      <h2>Sabores que vêm do oceano</h2>
      <p class="descricao">
        Conheça três ingredientes marcantes da gastronomia marinha.
        Toque nas imagens para conhecer cada um, suas características
        e dicas de preparo.
      </p>

      <div class="grade">
        <article class="card">
          <a class="imagem" href="#polvo" aria-label="Conhecer o polvo">
            <img src="https://images.unsplash.com/photo-1559737558-2f5a35f4523b?auto=format&fit=crop&w=800&q=85"
                 alt="Prato de frutos do mar">
          </a>
          <div class="card-conteudo">
            <h3>Polvo</h3>
            <p>Uma iguaria versátil, conhecida por sua textura delicada e sabor marcante.</p>
            <a class="link" href="#polvo">Descobrir o polvo →</a>
          </div>
        </article>

        <article class="card">
          <a class="imagem" href="#lagosta" aria-label="Conhecer a lagosta">
              <img src="https://receitascomairfryer.com.br/wp-content/uploads/2024/08/g2journey_httpss.mj_.run57fn66_4qdk_Close-up_of_two_grilled_lo_02ffa46e-6b86-480a-85b1-7fabd4aae1b2_1-1024x683.png"
                alt="Duas lagostas grelhadas">
          </a>
          <div class="card-conteudo">
            <h3>Lagosta</h3>
            <p>Um ingrediente sofisticado que combina com preparações simples e elegantes.</p>
            <a class="link" href="#lagosta">Descobrir a lagosta →</a>
          </div>
        </article>

        <article class="card">
          <a class="imagem" href="#camarao" aria-label="Conhecer o camarão">
            <img src="https://images.unsplash.com/photo-1565680018434-b513d5e5fd47?auto=format&fit=crop&w=800&q=85"
                 alt="Camarões preparados para uma refeição">
          </a>
          <div class="card-conteudo">
            <h3>Camarão</h3>
            <p>Prático e saboroso, é perfeito para receitas rápidas, massas e risotos.</p>
            <a class="link" href="#camarao">Descobrir o camarão →</a>
          </div>
        </article>
      </div>
    </section>

    <section class="faixa" id="polvo">
      <div class="artigo">
        <div class="subtitulo">Especialidade 01</div>
        <h2>Polvo: sabor e delicadeza</h2>
        <p>
          O polvo é muito apreciado em diferentes cozinhas do mundo.
          Seu sabor combina com azeite, alho, limão, ervas e legumes.
          Para obter uma boa textura, o preparo exige atenção ao tempo
          e ao método de cozimento.
        </p>

        <h3>Como escolher</h3>
        <ul>
          <li>Compre em estabelecimentos confiáveis.</li>
          <li>Observe a conservação e a aparência do produto.</li>
          <li>Prefira produtos mantidos sob refrigeração adequada.</li>
        </ul>

        <div class="receita">
          <h3>Receita: polvo com alho e azeite</h3>
          <p><strong>Ingredientes</strong></p>
          <ul>
            <li>Polvo limpo</li>
            <li>Azeite de oliva</li>
            <li>Alho picado</li>
            <li>Limão, sal e salsinha</li>
          </ul>
          <p><strong>Preparo:</strong> cozinhe o polvo até ficar macio.
          Corte em pedaços e finalize em uma frigideira com azeite e alho.
          Tempere com sal, limão e salsinha a gosto.</p>
        </div>
        <a class="link" href="#especialidades">↑ Voltar às especialidades</a>
      </div>
    </section>

    <section id="lagosta">
      <div class="artigo">
        <div class="subtitulo">Especialidade 02</div>
        <h2>Lagosta: um toque de sofisticação</h2>
        <p>
          A lagosta é um crustáceo valorizado pela carne delicada e
          pelo sabor característico. Preparações com manteiga, ervas
          e limão realçam seu sabor sem exigir muitos ingredientes.
        </p>

        <h3>Dicas de preparo</h3>
        <ul>
          <li>Compre de fornecedores confiáveis e respeite a cadeia de frio.</li>
          <li>Evite cozinhar por tempo excessivo, para não ressecar a carne.</li>
          <li>Combine com legumes, arroz ou batatas.</li>
        </ul>

        <div class="receita">
          <h3>Receita: lagosta na manteiga</h3>
          <p><strong>Ingredientes</strong></p>
          <ul>
            <li>Carne de lagosta devidamente preparada</li>
            <li>Manteiga</li>
            <li>Alho e limão</li>
            <li>Sal e ervas frescas</li>
          </ul>
          <p><strong>Preparo:</strong> cozinhe a lagosta adequadamente.
          Em uma frigideira, aqueça a manteiga com alho, acrescente a carne
          e finalize com limão e ervas. Sirva imediatamente.</p>
        </div>
        <a class="link" href="#especialidades">↑ Voltar às especialidades</a>
      </div>
    </section>

    <section class="faixa" id="camarao">
      <div class="artigo">
        <div class="subtitulo">Especialidade 03</div>
        <h2>Camarão: versatilidade à mesa</h2>
        <p>
          O camarão aparece em diversas receitas, de pratos leves
          a preparações cremosas. Seu cozimento costuma ser rápido,
          por isso é importante acompanhar o ponto para preservar
          a textura.
        </p>

        <h3>Limpeza e conservação</h3>
        <ul>
          <li>Mantenha o camarão refrigerado ou congelado conforme a embalagem.</li>
          <li>Descongele na geladeira, nunca por longos períodos em temperatura ambiente.</li>
          <li>Limpe e manuseie o alimento com utensílios higienizados.</li>
        </ul>

        <div class="receita">
          <h3>Receita: camarão ao alho e limão</h3>
          <p><strong>Ingredientes</strong></p>
          <ul>
            <li>Camarões limpos</li>
            <li>Alho picado</li>
            <li>Azeite ou manteiga</li>
            <li>Limão, sal e pimenta a gosto</li>
          </ul>
          <p><strong>Preparo:</strong> aqueça o azeite ou a manteiga,
          doure o alho e acrescente os camarões. Cozinhe até que estejam
          opacos e completamente cozidos. Finalize com limão e sirva.</p>
        </div>
        <a class="link" href="#especialidades">↑ Voltar às especialidades</a>
      </div>
    </section>

    <section id="contato">
      <div class="subtitulo">Fale conosco</div>
      <h2>Vamos conversar?</h2>
      <p>
        Tem sugestões de receitas, dúvidas ou ideias para o site?
        Entre em contato por e-mail.
      </p>
      <a class="botao"
         href="mailto:SEUEMAIL@EXEMPLO.COM?subject=Contato%20-%20Cozinha%20do%20Mar">
        Enviar e-mail
      </a>
      <p style="font-size:12px;margin-top:20px">
        Substitua SEUEMAIL@EXEMPLO.COM pelo seu endereço de e-mail.
      </p>
    </section>
  </main>

  <footer>
    <p>© 2026 Cozinha do Mar — Sabores e inspirações do oceano.</p>
    <p>Projeto desenvolvido em HTML e CSS.</p>
  </footer>

</body>
</html>
