
<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@300..700&display=swap" rel="stylesheet" />
  <title>Portifólio_Fernando Moreira</title>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <link rel="stylesheet" href="./css/main.css" />
</head>

<body>
  <header id="home" class="header">
    <div class="container">
      <div class="header__logo">
        <img src="./img/logo-header.svg" alt="logo" />
      </div>
      <nav class="header__nav">
        <ul class="header__list">
          <li class="header__item">
            <a href="#home" class="header__link">
              <span class="hdr-span hdr-SPN-Home">#</span>início
            </a>
          </li>
          <li class="header__item">
            <a href="#works" class="header__link"><span class="hdr-span hdr-SPN-Works">#</span>projetos</a>
          </li>
          <li class="header__item">
            <a href="#skills" class="header__link"><span class="hdr-span hdr-SPN-AboutMe">#</span>habilidades</a>
          </li>
          <li class="header__item">
            <a href="#about-me" class="header__link"><span class="hdr-span hdr-SPN-AboutMe">#</span>sobre</a>
          </li>
        </ul>
      </nav>
    </div>
    <div data-aos="fade-up" data-aos-anchor-placement="bottom-center" class="wrapper-social">
      <img src="./img/Line-10-Stroke.svg" alt="line-vetor" />
      <a id="id-lkdn" href="https://www.linkedin.com/in/feryamaha/" target="_blank" rel="noopener">
        <img src="./img/Linkedin.svg" alt="icon-linkedin" />
      </a>
      <a id="id-Gthb" href="https://github.com/feryamaha" target="_blank" rel="noopener">
        <img src="./img/Github.svg" alt="icon-github" />
      </a>
      <a id="id-Xai" href="https://x.com/_feryamaha" target="_blank" rel="noopener">
        <img src="./img/X.svg" alt="icon-X" />
      </a>
      <a id="id-Dscd" href="https://discord.com/channels/978717375362891776" target="_blank" rel="noopener">
        <img src="./img/Discord.svg" alt="icon-discord" />
      </a>
    </div>
  </header>

  <section class="s-hero-intro">
    <div class="container">
      <div class="ilustration-intro" data-aos="fade-up" data-aos-duration="3000">

        <img id="code-ilustration" src="./img/ilustration-Fcode.svg" alt="ilustration" data-aos="fade-down"
          data-aos-easing="linear" data-aos-duration="1500">
      </div>
      <div class="intro" data-aos="fade-up" data-aos-duration="3000">
        <div class="intro__text">
          <h1 class="intro__title">
            Fernando Moreira<br />Desenvolvedor<span>
              <br />
              front-end</span>
          </h1>
          <p class="intro__description">
            Dou vida ao seu design. <br />
            Páginas web com precisão em cada elemento.
          </p>
        </div>
      </div>


    </div>
    <img id="logo-brush" src="./img/mask-fernando-moreira.svg" alt="-logo-fernando">
    <img id="img-brush" src="./img/brush-02.svg" alt="brush">
  </section>


  <section id="works" class="s-hero-projects">
    <div class="box-headline">
      <img id="headline" src="./img/Line.svg" alt="line">
      <p><span class="hdr-span">#</span>PROJETOS</p>
    </div>

    <div class="container">
      <!-- <div class="slider-track"> -->
      <!--projeto MLX CAPITAL_AUCLAN DESIGN-->
      <div class="wrapper__cards" data-aos="zoom-in-left">
        <div class="proj-card__image">
          <img src="./img/frame_mlx.webp" alt="image-MLX" data-aos="fade-up" data-aos-duration="2000" />
          <div class="title-proj-image">
            <h1 class="title-project ">MLX CAPITAL</h1>
            <h2>HTML CSS JAVASCRIPT</h2>
            <p>Frontend desenvolvido na <a class="auclan-design" href="https://auclandesign.com/" target="_blank"
                rel="noopener noreferrer">Auclan Design</a> para o cliente MLX CAPITAL.</p>
            <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
              data-aos-duration="2500">
              <a class="btn-card bt-title-image" href="https://feryamaha.github.io/MLX-2025/" target="_blank"
                rel="noopener noreferrer">Ver o projeto</a>
              <p class="Obs_LGPD title-image">Nota: Este deploy é uma versão preliminar, não refatorada como projeto
                final,
                servindo
                apenas como prévia de apresentação de projeto|experiência. <br> O link oficial não será divulgado
                devido
                a LGPD e direitos legais do cliente.</p>
            </div>
          </div>
        </div>
        <div class="proj-text-cotent" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
          data-aos-duration="2200">
          <h1 class="title-project">MLX CAPITAL</h1>
          <h2>HTML CSS JAVASCRIPT</h2>
          <p>Frontend desenvolvido na <a class="auclan-design" href="https://auclandesign.com/" target="_blank"
              rel="noopener noreferrer">Auclan Design</a> para o cliente MLX CAPITAL.</p>
          <div class="description-proj">
            <p>Estrutura semântica em HTML5 com seções <span>header, section, footer</span> e elementos como
              <span>nav</span> e <span>img com alt</span>, assegurando acessibilidade e otimização para SEO.
            </p>
            <p>CSS modular com arquivos distintos <span>main.css, components.css, grid.css</span>, variáveis em
              <span>:root</span> (ex.: <span>--black-700</span>), grid responsivo e animações refinadas com
              <span>transition</span> e <span>.service-card:hover</span>.
            </p>
            <p>JavaScript interativo com carrossel contínuo usando <span>requestAnimationFrame e translateX</span> e
              menu responsivo via <span>addEventListener e classList</span>, integrando manipulação eficiente do DOM
              para interfaces modernas.</p>
          </div>
          <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
            data-aos-duration="2500">
            <a class="btn-card" href="https://feryamaha.github.io/MLX-2025/" target="_blank"
              rel="noopener noreferrer">Ver o projeto</a>
            <p class="Obs_LGPD">Nota: Este deploy é uma versão preliminar, não refatorada como projeto final, servindo
              apenas como prévia de apresentação de projeto|experiência. <br> O link oficial não será divulgado devido
              a LGPD e direitos legais do cliente.</p>
          </div>
        </div>
      </div>

      <!--projeto ALPHA_AUCLAN DESIGN-->
      <!--         <div class="wrapper__cards" data-aos="zoom-in-left">
          <div class="proj-card__image">
            <img src="./img/frame-alpha.webp" alt="image-ALPHA" data-aos="fade-up" data-aos-duration="2000" />
            <div class="title-proj-image">
              <h1 class="title-project">ALPHA</h1>
              <h2>HTML CSS JAVASCRIPT</h2>
              <p>Frontend desenvolvido na <a class="auclan-design" href="https://auclandesign.com/" target="_blank"
                  rel="noopener noreferrer">Auclan Design</a> para o cliente ALPHA.</p>
              <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
                data-aos-duration="2500">
                <a class="btn-card" href="https://feryamaha.github.io/ALPHA-2025/" target="_blank"
                  rel="noopener noreferrer">Ver o projeto</a>
                <p class="Obs_LGPD">Nota: Este deploy é uma versão preliminar, não refatorada como projeto final,
                  servindo
                  apenas como prévia de apresentação de projeto|experiência. <br> O link oficial não será divulgado
                  devido
                  a LGPD e direitos legais do cliente.</p>
              </div>
            </div>
          </div>
          <div class="proj-text-cotent" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
            data-aos-duration="2200">
            <h1 class="title-project">ALPHA</h1>
            <h2>HTML CSS JAVASCRIPT</h2>
            <p>Frontend desenvolvido na <a class="auclan-design" href="https://auclandesign.com/" target="_blank"
                rel="noopener noreferrer">Auclan Design</a> para o cliente ALPHA.</p>
            <div class="description-proj">
              <p>Estrutura semântica em HTML5 com seções <span>header, section, footer</span> e elementos como
                <span>nav</span> e <span>img com alt</span>, assegurando acessibilidade e otimização para SEO.
              </p>
              <p>CSS modular com arquivos distintos <span>main.css, components.css, grid.css</span>, variáveis em
                <span>:root</span> (ex.: <span>--black-700</span>), grid responsivo e animações refinadas com
                <span>transition</span> e <span>.service-card:hover</span>.
              </p>
              <p>JavaScript interativo com carrossel contínuo usando <span>requestAnimationFrame e translateX</span> e
                menu responsivo via <span>addEventListener e classList</span>, integrando manipulação eficiente do DOM
                para interfaces modernas.</p>
            </div>
            <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
              data-aos-duration="2500">
              <a class="btn-card" href="https://feryamaha.github.io/ALPHA-2025/" target="_blank"
                rel="noopener noreferrer">Ver o projeto</a>
              <p class="Obs_LGPD">Nota: Este deploy é uma versão preliminar, não refatorada como projeto final, servindo
                apenas como prévia de apresentação de projeto|experiência. <br> O link oficial não será divulgado devido
                a LGPD e direitos legais do cliente.</p>
            </div>
          </div>
        </div> -->

      <!--projeto VEGA_AUCLAN DESIGN-->
      <!--<div class="wrapper__cards" data-aos="zoom-in-left">
          <div class="proj-card__image">
            <img src="./img/frame-vega.webp" alt="image-vega" data-aos="fade-up" data-aos-duration="2000" />
            <div class="title-proj-image">
              <h1 class="title-project">VEGA</h1>
              <h2>HTML SCSS JAVASCRIPT</h2>

              <p>Frontend desenvolvido na <a class="auclan-design" href="https://auclandesign.com/" target="_blank"
                  rel="noopener noreferrer">Auclan Design</a> para o cliente VEGA.</p>
              <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
                data-aos-duration="2500">
                <a class="btn-card" href="https://mayconmartins01.github.io/websitevega/" target="_blank"
                  rel="noopener noreferrer">Ver o projeto</a>
                <p class="Obs_LGPD">Nota: Este deploy é uma versão preliminar, não refatorada como projeto final,
                  servindo
                  apenas como prévia de apresentação de projeto|experiência. <br> O link oficial não será divulgado
                  devido
                  a LGPD e direitos legais do cliente.</p>
              </div>
            </div>
          </div>
          <div class="proj-text-cotent" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
            data-aos-duration="2200">
            <h1 class="title-project">VEGA</h1>
            <h2>HTML SCSS JAVASCRIPT</h2>

            <p>Frontend desenvolvido na <a class="auclan-design" href="https://auclandesign.com/" target="_blank"
                rel="noopener noreferrer">Auclan Design</a> para o cliente VEGA.</p>
            <div class="description-proj">
              <p>Estrutura semântica em HTML5 com seções <span>header, section, footer</span> e elementos como
                <span>nav</span> e <span>img com alt</span>, assegurando acessibilidade e otimização para SEO.
              </p>
              <p>CSS modular com arquivos distintos <span>main.css, components.css, grid.css</span>, variáveis em
                <span>:root</span> (ex.: <span>--black-700</span>), grid responsivo e animações refinadas com
                <span>transition</span> e <span>.service-card:hover</span>.
              </p>
              <p>JavaScript interativo com carrossel contínuo usando <span>requestAnimationFrame e translateX</span> e
                menu responsivo via <span>addEventListener e classList</span>, integrando manipulação eficiente do DOM
                para interfaces modernas.</p>
            </div>
            <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
              data-aos-duration="2500">
              <a class="btn-card" href="https://mayconmartins01.github.io/websitevega/" target="_blank"
                rel="noopener noreferrer">Ver o projeto</a>
              <p class="Obs_LGPD">Nota: Este deploy é uma versão preliminar, não refatorada como projeto final, servindo
                apenas como prévia de apresentação de projeto|experiência. <br> O link oficial não será divulgado devido
                a LGPD e direitos legais do cliente.</p>
            </div>
          </div>
        </div> -->


      <!--projeto AUTODATAF-->
      <!--         <div class="wrapper__cards" data-aos="zoom-in-left">
          <div class="proj-card__image">
            <img src="./img/frame-autodataF.webp" alt="image-AutodataF" data-aos="fade-up" data-aos-duration="2000" />
            <div class="title-proj-image">
              <h1 class="title-project">AUTODATAF</h1>
              <h2>REACT CSS-MODULES NODE.JS/EXPRESS POSTGRESQL(NEON) BCRYPT CORS VITE VERCEL</h2>
              <p>Autodata.F organiza cursos gratuitos do YouTube para estudo focado de programação.</p>
              <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
                data-aos-duration="2500">
                <a class="btn-card" href="https://autodata-f.vercel.app/" target="_blank" rel="noopener noreferrer">Ver
                  o
                  projeto</a>
                <p class="Obs_LGPD">Nota: Autodata.F é um projeto pessoal, criado para praticar
                  programação e organizar estudos com cursos gratuitos do YouTube. Não é aberto ao público e não tem
                  fins
                  lucrativos. Todos os conteúdos pertencem aos seus criadores originais.</p>
              </div>
            </div>
          </div>
          <div class="proj-text-cotent" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
            data-aos-duration="2200">
            <h1 class="title-project">AUTODATAF</h1>
            <h2>REACT CSS-MODULES NODE.JS/EXPRESS POSTGRESQL(NEON) BCRYPT CORS VITE VERCEL</h2>
            <p>Autodata.F organiza cursos gratuitos do YouTube para estudo focado de programação.</p>
            <div class="description-proj">
              <p>Desenvolvida com React e CSS Modules no frontend, e Node.js com Express e PostgreSQL (Neon) no backend,
                Autodata.F oferece um ambiente seguro e interativo. Suas funcionalidades incluem um formulário de
                gerenciamento protegido por senha, navegação por cards responsivos, player de vídeo integrado via API
                React-YouTube, e temas que alternam automaticamente.</p>
              <p>A plataforma Autodata.F está em constante evolução e contará com a IA 'Yaminuelle', inspirada nas
                filhas do criador, Anthonella e Yasmim Emanuelle. Atualmente em fase de desenvolvimento e treinamento,
                ela permitirá pesquisas avançadas dentro da plataforma e na internet, por comandos de voz e texto,
                facilitando o acesso a cursos, vídeos e conteúdos relevantes.</p>
            </div>
            <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
              data-aos-duration="2500">
              <a class="btn-card" href="https://autodata-f.vercel.app/" target="_blank" rel="noopener noreferrer">Ver o
                projeto</a>
              <p class="Obs_LGPD">Nota: Autodata.F é um projeto pessoal, criado para praticar
                programação e organizar estudos com cursos gratuitos do YouTube. Não é aberto ao público e não tem fins
                lucrativos. Todos os conteúdos pertencem aos seus criadores originais.</p>
            </div>
          </div>
        </div> -->

      <!--projeto PULSE COLOR-->
      <!--       <div class="wrapper__cards" data-aos="zoom-in-left">
          <div class="proj-card__image">
            <img src="./img/frame-pulse-COLOR.webp" alt="image-PulseColor" data-aos="fade-up"
              data-aos-duration="2000" />
            <div class="title-proj-image">
              <h1 class="title-project">PULSE COLOR</h1>
              <h2>HTML SASS JAVASCRIPT</h2>
              <p>Pulse Color é um projeto de portfólio que explora animações e interatividade com cores, formas e sons,
                criado a partir de exercícios de estudo das tecnologias aplicadas.</p>
              <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
                data-aos-duration="2500">
                <a class="btn-card" href="https://feryamaha.github.io/SASS/" target="_blank"
                  rel="noopener noreferrer">Ver
                  o projeto</a>
              </div>
            </div>
          </div>
          <div class="proj-text-cotent" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
            data-aos-duration="2200">
            <h1 class="title-project">PULSE COLOR</h1>
            <h2>HTML SASS JAVASCRIPT</h2>
            <p>Pulse Color é um projeto de portfólio que explora animações e interatividade com cores, formas e sons,
              criado a partir de exercícios de estudo das tecnologias aplicadas.</p>
            <div class="description-proj">
              <p>Desenvolvido com HTML5, SASS e JavaScript, o projeto apresenta seções hero com efeitos de pulsação,
                ondas e transições de cor por letra. Dez esferas geométricas animadas movem-se pela tela, colidem, mudam
                de cor e forma (círculo, quadrado, triângulo, etc.), e podem ser arrastadas pelo usuário, com feedback
                sonoro via Web Audio API.</p>
              <p>O projeto também inclui um cursor personalizado com rastro, gradiente de fundo animado e design
                responsivo ajustado por media queries. Animações são gerenciadas com a biblioteca AOS, e cores
                complementares são obtidas via API (thecolorapi.com), enriquecendo a experiência interativa.</p>
            </div>
            <div class="deploy-proj" data-aos="fade-right" data-aos="fade-down" data-aos-easing="linear"
              data-aos-duration="2500">
              <a class="btn-card" href="https://feryamaha.github.io/SASS/" target="_blank" rel="noopener noreferrer">Ver
                o projeto</a>
            </div>
          </div>
        </div> -->
      <!-- </div> --> <!-- Fim do .slider-track -->

      <div class="ctrl-slide">
        <button id="bt-ctrl-back">back</button>
        <div class="line-ctrl-btn">
          <img src="./img/Line.svg" alt="line">
        </div>
        <button id="bt-ctrl-next">next</button>
      </div>
    </div>
  </section>

  <section id="skills" class="s-hero-skills">
    <img id="logo-brush-proj" src="./img/mask-fernando-moreira.svg" alt="-logo-fernando">
    <img id="img-brush-proj" src="./img/brush-02.svg" alt="brush">
    <div class="container">
      <div class="skills__header">
        <div class="wrapper__skills">
          <p><span class="hdr-span">#</span>skills</p>
          <img src="./img/line-stroke-header.svg" alt="line-svg" />
        </div>
        <!--  <a href="#" target="_blank" class="skills-view-all">View all ~~></a> -->
      </div>
      <div data-aos="fade-down" data-aos-easing="linear" data-aos-duration="1500" class="key-skills">
        <div class="keySK-title">
          <p>[...NÍVEIS DE HABILIDADE...]</p>
        </div>
        <div class="ksk-dcrpt">
          <div class="know-box">
            <img id="CWK" src="./img/circle-white-key.svg" alt="circle-key" />
            <p>Básico</p>
          </div>
          <div class="know-box">
            <img id="CBK" src="./img/circle-blue-key.svg" alt="circle-key" />
            <p>Intermediário</p>
          </div>
          <div class="know-box">
            <img id="CPK" src="./img/circle-purple-key.svg" alt="circle-key" />
            <p>Pleno</p>
          </div>
          <div class="know-box">
            <img id="CBrnK" src="./img/circle-brown-key.svg" alt="circle-key" />
            <p>Avançado</p>
          </div>
        </div>
      </div>

      <div class="wrapper-card-skills">
        <div data-aos="fade-up" data-aos-duration="3000" class="card-skills card-skl">
          <img id="rtg-skL1" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-skL2" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-skL3" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-skL4" src="./img/Rectangle.svg" alt="retangle-border">
          <div class="cdsk-title">
            <p>LINGUAGENS</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box AdKn">
              <p class="hover-text">Javascript</p>
              <img src="./img/circle-blue-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Typescript</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Python</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">PHP</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">HTML</p>
              <img src="./img/circle-brown-key.svg" alt="circle-key" />
            </div>
          </div>
        </div>

        <div data-aos="fade-down" class="card-skills card-frm">
          <img id="rtg-frm1" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-frm2" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-frm3" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-frm4" src="./img/Rectangle.svg" alt="retangle-border">
          <div class="cdsk-title">
            <p>FRAMEWORKS</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box AdKn">
              <p class="hover-text">React</p>
              <img src="./img/circle-blue-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Next.js</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Vue.js</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Angular</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
          </div>
        </div>

        <div data-aos="fade-up" data-aos-duration="3000" class="card-skills card-dv">
          <img id="rtg-dv1" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-dv2" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-dv3" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-dv4" src="./img/Rectangle.svg" alt="retangle-border">
          <div class="cdsk-title">
            <p>DESIGN VISUAL</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box AdKn">
              <p class="hover-text">CSS</p>
              <img src="./img/circle-brown-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">CSS Modules</p>
              <img src="./img/circle-brown-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Sass</p>
              <img src="./img/circle-purple-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Scss</p>
              <img src="./img/circle-purple-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Tailwind</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Bootstrap</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
          </div>
        </div>

        <div data-aos="fade-down" class="card-skills card-tol">
          <img id="rtg-tol1" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-tol2" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-tol3" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-tol4" src="./img/Rectangle.svg" alt="retangle-border">
          <div class="cdsk-title">
            <p>TOOLS</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box AdKn">
              <p class="hover-text">Vscode</p>
              <img src="./img/circle-brown-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Git</p>
              <img src="./img/circle-purple-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Github</p>
              <img src="./img/circle-brown-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Vercel</p>
              <img src="./img/circle-purple-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Figma</p>
              <img src="./img/circle-blue-key.svg" alt="circle-key" />
            </div>
          </div>
        </div>

        <div data-aos="fade-up" data-aos-duration="3000" class="card-skills card-dpi">
          <img id="rtg-dpi1" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-dpi2" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-dpi3" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-dpi4" src="./img/Rectangle.svg" alt="retangle-border">
          <div class="cdsk-title">
            <p>DADOS e API</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box AdKn">
              <p class="hover-text">PostgreSQL</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Node.js</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">Consumo de API</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text"> Chamadas HTTP</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
            <div class="skills-box AdKn">
              <p class="hover-text">REST</p>
              <img src="./img/circle-white-key.svg" alt="circle-key" />
            </div>
          </div>
        </div>
      </div>
      <img id="rtg-left-skills" src="./img/rectangle-right.svg" alt="retanggle" />
    </div>
  </section>

  <section id="about-me" class="s-hero-about">
    <div class="container">
      <div class="about__header">
        <div class="wrapper__skills">
          <p><span class="hdr-span">#</span>Sobre-mim</p>
          <img src="./img/line-stroke-header.svg" alt="line-svg" />
        </div>
        <!-- <a href="#" target="_blank" class="about-view-all">View all ~~></a> -->
      </div>
      <div class="wrapper-about-me">
        <div data-aos="fade-up" data-aos-anchor-placement="top-bottom" class="wrapper-about">
          <p>Olá, eu sou Fernando Moreira da Silva!</p>
          <p>
            Sou um desenvolvedor front-end autodidata. Posso desenvolver sites
            responsivos do zero e elevá-los a experiências web modernas,
            amigáveis e resposivas.
          </p>
          <p>
            Desde 2022, passei por uma transição de carreira e venho me
            dedicando ao desenvolvimento Front-End, atuando como freelancer e
            prestador de serviços. <br />
            Antes disso, acumulei 18 anos de experiência na indústria como
            Metrologista, com formação em Técnico em Plástico e Metrologia
            Avançada para engenharia reversa. <br />
            Hoje, meu foco é 100% em desenvolvimento Front-End, entregando
            soluções web de alta qualidade em Pixel Perfect.
          </p>
        </div>
        <div data-aos="fade-down" data-aos-easing="linear" data-aos-duration="1500" class="box-image-about">
          <img id="img-profile-about" src="./img/profile-about.webp" alt="profile-about" />
          <img id="rtg-abt-1" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-abt-2" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-abt-3" src="./img/Rectangle.svg" alt="retangle-border">
          <img id="rtg-abt-4" src="./img/Rectangle.svg" alt="retangle-border">
          <div class="image-logo-about" data-aos="fade-up" data-aos-duration="3000">
            <img id="logo-about" src="./img/logo0.svg" alt="logo" />

            <p id="p-text-abt">PIXEL PERFECT</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <footer>
    <div class="container">
      <div class="wrapper-footer">
        <div class="logo-footer">
          <img src="./img/logo-header.svg" alt="logo" />
          <p>Desenvolvedor Front-END</p>
        </div>

        <div class="social-footer">
          <a id="id-lkdn" href="https://www.linkedin.com/in/feryamaha/" target="_blank" rel="noopener">
            <img src="./img/Linkedin.svg" alt="icon-linkedin" />
          </a>
          <a id="id-Gthb" href="https://github.com/feryamaha" target="_blank" rel="noopener">
            <img src="./img/Github.svg" alt="icon-github" />
          </a>
          <a id="id-Xai" href="https://x.com/_feryamaha" target="_blank" rel="noopener">
            <img src="./img/X.svg" alt="icon-X" />
          </a>
          <a id="id-Dscd" href="https://discord.com/channels/978717375362891776" target="_blank" rel="noopener">
            <img src="./img/Discord.svg" alt="icon-discord" />
          </a>
        </div>
      </div>
      <p>©Copyright_2025. Feito por Fernando Moreira</p>
    </div>
  </footer>
  <!-- MENU MOBILE -->
  <div class="float-nav">
    <a href="#" class="menu-btn">
      <ul>
        <li class="line"></li>
        <li class="line"></li>
        <li class="line"></li>
      </ul>
      <div class="menu-txt">menu</div>
    </a>
  </div>

  <div class="main-nav">
    <div class="header__logo">
      <img src="./img/logo-header.svg" alt="logo" />
    </div>
    <ul>
      <li class="header__item">
        <a href="#home" class="header__link">
          <span class="hdr-span hdr-SPN-Home">#</span>início
        </a>
      </li>
      <li class="header__item">
        <a href="#works" class="header__link"><span class="hdr-span hdr-SPN-Works">#</span>projetos</a>
      </li>
      <li class="header__item">
        <a href="#skills" class="header__link"><span class="hdr-span hdr-SPN-AboutMe">#</span>habilidades</a>
      </li>
      <li class="header__item">
        <a href="#about-me" class="header__link"><span class="hdr-span hdr-SPN-AboutMe">#</span>sobre</a>
      </li>
    </ul>

  </div>
</body>

</html>
<script src="./js/js/main.js"></script>
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init();
</script>
