# c-mariee.github.io

<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      background-color: #2F4F4F;
      color: #FFE4E1;
    }
    nav {
      background-color: #FFB6C1;
      padding: 10px;
    }
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin-right: 100px;
    }
    nav ul li a {
      color: #FFFAF0;
      text-decoration-line: underline;
      text-decoration-style: solid;
      text-decoration-color:#FFFAF0;
      font-size: 1.5rem;
      font-family: "Gill Sans";
    }
    nav ul li a:hover {
      text-decoration: underline;
      font-weight: bold;
    }
    .banner {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
    }
    .banner h1 {
      font-size: 56px;
      font-family: "Gill Sans";
      color: #FFFAF0;
      text-align: center;
      margin-bottom: 20px;
      animation-direction: normal;
    }
    .banner h2 {
      font-size: 28px;
      font-family: "Gill Sans";
      color: #F0FFF0;
      text-align: center;
      margin-bottom: 20px;
    }
    @keyframes fade {
      0% {
        opacity: 1;
      }
      50% {
        opacity: 0.5;
      }
      100% {
        opacity: 1;
      }
    }
    @keyframes slide {
      0% {
        transform: translateX(0);
      }
      50% {
        transform: translateX(-10px);
      }
      100% {
        transform: translateX(0);
      }
    }
    .banner p {
      font-size: 24px;
      font-family: "Gill Sans";
      text-align: center;

    }
    .section {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
    }
    .section h2 {
      font-size: 36px;
      font-family: "Gill Sans";
      color: #FFE4E1;
      text-align: center;
      margin-bottom: 20px;
      border: 4px dashed #FFB6C1;
      padding: 10px;
    }
    .section p {
      font-size: 18px;
      font-family: "Gill Sans";
      text-align: center;
    }
    .section ul {
      list-style-type: none;
      padding: 0;
      margin: 20px;
    }
    .section ul li {
      margin-bottom: 10px;
    }
    .links {
      background-color: #FFFAF0;
      padding: 20px;
    }
    .links a {
      color: #FFFAF0;
      font-weight: bold;
    }
    .portfolio-picture {
      border: 5px solid #FFE4E1;
      max-width: 75%;
      display: block;
      margin: 0 auto;
    }
    .github-container {
  display: flex;
  align-items: center;
}
.dropdown {
  position: relative;
}

.dropdown-content {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background-color: #FFE4E1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  color: #2F4F4F;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown-content .icon {
  display: inline-block;
  width: 20px;
  height: 20px;
  margin-right: 5px;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.video-container {
  display: flex;
  justify-content: center;
  margin-top: 30px;
}

.about-grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 20px;
  align-items: start;
  margin-top: 20px;
}

.column {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  word-wrap: break-word;
}

.column h4 {
  margin-bottom: 10px;
}

.portfolio-picture {
  max-width: 100%;
  max-height: 300px;
}
.button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #FFE4E1;
      color: #2F4F4F;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 10px;
      font-family: "Gill Sans";
    }
.button2 {
    display: inline-block;
      padding: 10px 20px;
      background-color: #FFE4E1;
      color: #2F4F4F;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 10px;
      font-family: "Gill Sans";
}
.button3 {
      display: inline-flex;
      align-items: center;
      padding: 10px 20px;
      background-color: #FFE4E1;
      color: #2F4F4F;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 10px;
      font-family: "Gill Sans";
    }
    .button3 .icon {
      margin-right: 5px;
      width: 20px; /* Adjust the size as needed */
      height: 20px; /* Adjust the size as needed */
    }
  </style>
</head>
<body>
    <nav>
        <ul>
          <li><a href="portfolio.html">Home</a></li>
          <li><a href="projects.html">Projects</a></li> 
          <li class="dropdown">
            <a href="javascript:void(0)">Connect</a>
            <div class="dropdown-content">
              <a href="CheyenneMiller_Resume.pdf">Resume</a>
              <a href="https://www.linkedin.com/in/cheyenne-miller-97089174/">LinkedIn</a>
              <a href="https://github.com/c-mariee">GitHub</a>
            </div>
          </li>
        </ul>
      </nav>      
  <section id="home" class="banner">
    <h1 class="font-weight-bold">Cheyenne Miller</h1>
    <h2>Este portafolio es la culminación de lo que he aprendido hasta la fecha y expresado de una manera que es únicamente mía.
    <h3>"Hay una diferencia vital entre practicar para obtener algo que crees que te falta y practicar para expresar la plenitud de quien eres."</h3>
    <a class="button3" href="#">
        <img class="icon" src="GitHubLogo.jpg" alt="GitHub Logo">
        View GitHub
      </a>
    <div class="video-container">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/nPBVaUP5onM" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </div>
  </section>  

  <section id="about" class="section">
    <h2>About Me</h2>
    <div class="about-grid">
      <div class="column">
        <h4>Un poco sobre mi</h4>
        <p>Soy gerente de cumplimiento de productos en una startup tecnológica y estoy incursionando en el mundo del desarrollo full stack. Me apasiona crear procesos eficientes y efectivos, realizar pruebas y aseguramiento de calidad, y ayudar a los equipos a resolver problemas para escalar programas. Este sitio web marca el comienzo de mi camino hacia el desarrollo full stack y estoy emocionada por seguir creciendo.</p>
      </div>
      <div class="column">
        <img class="portfolio-picture" src="Portfolio Picture.jpg" alt="Portfolio Picture">
        <a class="button" href="CheyenneMiller_Resume.pdf" target="_blank">Download Resume</a>
        <a class="button2" href="https://www.linkedin.com/in/cheyenne-miller-97089174/">View LinkedIn</a>
      </div>
      <div class="column">
        <h4>A little about me</h4>
        <p>My name is Cheyenne and I'm a product compliance manager at a fintech, and I'm taking the opportunity explore the full stack development space. I'm passionate about creating efficient and effective processes, conducting testing and quality assurance, and helping teams solve problems to scale programs. This website marks the beginning of my journey towards full stack development, and I'm excited you've landed on my page.</p>
      </div>
    </div>
  </section>  
</body>
</html>
