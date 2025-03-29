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

  <style>
    .skills-box {
      display: flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 10px;
    }
    .skills-box img {
      width: 20px;
      height: 20px;
    }
    .cdsk-dcrpt {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      gap: 20px;
    }
  </style>
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
  </header>

  <section id="skills" class="s-hero-skills">
    <div class="container">
      <div class="skills__header">
        <div class="wrapper__skills">
          <p><span class="hdr-span">#</span>skills</p>
        </div>
      </div>

      <div class="wrapper-card-skills">
        <div class="card-skills card-skl">
          <div class="cdsk-title">
            <p>LINGUAGENS</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box">
              <p>Javascript</p>
              <img src="https://img.shields.io/badge/Javascript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="Javascript" />
            </div>
            <div class="skills-box">
              <p>Typescript</p>
              <img src="https://img.shields.io/badge/Typescript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="Typescript" />
            </div>
            <div class="skills-box">
              <p>Python</p>
              <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
            </div>
            <div class="skills-box">
              <p>PHP</p>
              <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
            </div>
            <div class="skills-box">
              <p>HTML</p>
              <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML" />
            </div>
          </div>
        </div>

        <div class="card-skills card-frm">
          <div class="cdsk-title">
            <p>FRAMEWORKS</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box">
              <p>React</p>
              <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
            </div>
            <div class="skills-box">
              <p>Next.js</p>
              <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
            </div>
            <div class="skills-box">
              <p>Vue.js</p>
              <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
            </div>
            <div class="skills-box">
              <p>Angular</p>
              <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
            </div>
          </div>
        </div>

        <div class="card-skills card-dv">
          <div class="cdsk-title">
            <p>DESIGN VISUAL</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box">
              <p>CSS</p>
              <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" />
            </div>
            <div class="skills-box">
              <p>CSS Modules</p>
              <img src="https://img.shields.io/badge/CSS%20Modules-000000?style=for-the-badge&logo=cssmodules&logoColor=white" alt="CSS Modules" />
            </div>
            <div class="skills-box">
              <p>Sass</p>
              <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="Sass" />
            </div>
            <div class="skills-box">
              <p>Scss</p>
              <img src="https://img.shields.io/badge/Scss-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="Scss" />
            </div>
            <div class="skills-box">
              <p>Tailwind</p>
              <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind" />
            </div>
            <div class="skills-box">
              <p>Bootstrap</p>
              <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
            </div>
          </div>
        </div>

        <div class="card-skills card-tol">
          <div class="cdsk-title">
            <p>TOOLS</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box">
              <p>Vscode</p>
              <img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="Vscode" />
            </div>
            <div class="skills-box">
              <p>Git</p>
              <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
            </div>
            <div class="skills-box">
              <p>Github</p>
              <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Github" />
            </div>
            <div class="skills-box">
              <p>Vercel</p>
              <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
            </div>
            <div class="skills-box">
              <p>Figma</p>
              <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />
            </div>
          </div>
        </div>

        <div class="card-skills card-dpi">
          <div class="cdsk-title">
            <p>DADOS e API</p>
          </div>
          <div class="cdsk-dcrpt">
            <div class="skills-box">
              <p>PostgreSQL</p>
              <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
            </div>
            <div class="skills-box">
              <p>Node.js</p>
              <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node-dot-js&logoColor=white" alt="Node.js" />
            </div>
            <div class="skills-box">
              <p>Consumo de API</p>
              <img src="https://img.shields.io/badge/API-FF6F00?style=for-the-badge&logo=api&logoColor=white" alt="Consumo de API" />
            </div>
            <div class="skills-box">
              <p>Chamadas HTTP</p>
              <img src="https://img.shields.io/badge/HTTP-228B22?style=for-the-badge&logo=http&logoColor=white" alt="Chamadas HTTP" />
            </div>
            <div class="skills-box">
              <p>REST</p>
              <img src="https://img.shields.io/badge/REST-02569B?style=for-the-badge&logo=rest&logoColor=white" alt="REST" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</body>

</html>
