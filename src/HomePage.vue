<template>
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=PT+Sans+Caption:wght@400;700&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <nav class="head">
                <img src="./assets/devionLogo.png" alt="">
                <h3>Mon Portfolio</h3>
                <a href="./404.vue" target="_blank"><h3>Mes adresses</h3></a>
            </nav>
        </header>
    <div class="main-container" id="main-container">
      <div class="container-one">
          <div class="profile">
              <img src="./assets/pp.jpg" alt="">
              <h3>Kevin LEAO</h3>
              <p>Développeur Web</p>
          </div>

      </div>
  
      <div class="container-two">
          <div class="about-me">
              <h1>A Propos de moi</h1>
              <p> Je suis Kevin LEAO, un professionnel déterminé de 28 ans avec une passion 
                pour le développement web et mobile. Après avoir passé 7 ans dans le secteur 
                exigeant de la restauration, j'ai pris la décision courageuse de me réorienter 
                vers le domaine du développement web en début d'année 2024. Animé par ma soif 
                d'apprendre et de m'adapter aux nouvelles technologies, j'ai entrepris une formation 
                intensive pour obtenir le diplôme de Développeur Web et Mobile au Centre Européen de Formation.</p>
          </div>
          <div class="technology-section">
              <h1>Technologies Etudiées</h1>
              <img src="./assets/htmlLogo.png" alt="">
              <img src="./assets/cssLogo.png" alt="">
              <img src="./assets/jsLogo.png" alt="">
          </div>
          <div class="button-container">
            <div class="projects-button">
                  <a href="#contact">Mon CV</a>
              </div>
              <div class="projects-button">
                  <a href="#project-one">Mes Projets</a>
              </div>
              <div class="projects-button">
                  <a href="#contact">Me Contacter</a>
              </div>
          </div>
      </div>
  </div> 
  <div class="projects">
    <div class="project-one" id="project-one">
        <h1>Project one</h1>
        <img src="./assets/project1.jpg" alt="">
    </div>
    <div class="project-two">
        <h1>Project Two</h1>
        <img src="./assets/project1.jpg" alt="">
    </div>
    <div class="project-three">
        <h1>Project three</h1>
        <img src="./assets/project1.jpg" alt="">
    </div>
  </div>   
  <div class="contact" id="contact">
    <h1>Contactez-moi</h1>
    <form action="#">
        <label for="name">Nom:</label>
        <br>
        <input type="text" id="name" name="name">
        <br>
        <label for="email">Email:</label>
        <br>
        <input type="text" id="email" name="email">
        <br>
        <label for="objet">Objet:</label>
        <br>
        <input type="text" id="objet" name="objet">
        <br>
        <label for="message">Message:</label>
        <br>
        <textarea name="message" id="message" cols="30" rows="10"></textarea>
        <br>
        <input type="submit" value="Envoyer" id="envoyer">
    </form>

  </div>
 <a href="#main-container">
    <div class="return-to-top">
        <img src="./assets/fleche-haut.png" alt="">
    </div>
  </a>
  </body>
  <footer>
    <div class="footer">
        <div class="social-links">
                  <div class="link">
                      <a href="https://github.com/dwleao/MonPortfolio" target="_blank">
                          <img src="./assets/githubLogo.png" alt="" >
                      </a>
                  </div>
                  <div class="link">
                      <a href="https://www.linkedin.com/in/kevin-leao-10a6161aa/" target="_blank">
                          <img src="./assets/linkedinLogo.png" alt="">
                      </a>
                  </div>
                  <div class="link">
                      <a href="https://www.instagram.com/kevinleao_/" target="_blank">
                          <img src="./assets/instagramLogo.png" alt="">
                      </a>
                  </div>
          </div>
    </div>
  </footer>
</template>

<script>

</script>

<style scoped>

  .main-container{
      font-family: "PT Sans Caption", sans-serif;
      font-weight: 400;
      font-style: normal;
      color: #2c3e50;
      display: flex;
      flex-direction: row;
      background-color: #F1F1D3;
      border-radius: 25px;
  }

  .container-one {
      background-color: #7DC2A5;
      padding: 2.5%;
      width: 30%;
      border-radius: 25px;
      text-align: center;
  }

  .profile img{
      height: 5rem;
      border-radius: 50%;
  }

  .link a {
      text-decoration: none;
      color: #2c3e50;
      font-size: 12px;
  }

  .link img {
      height: 2.5rem;
  }
  
  .link img:hover {
    opacity: 0.6;
  }

  .container-two {
      background-color: #F1F1D3;
      margin: 2.5%;
      width: 70%;
  }

  .about-me {
      text-align: left;
      text-align: center;
  }

  .technology-section {
    text-align: center;
  }

  .technology-section img {
      height: 2.5rem;

  }

  .button-container {
      margin-top: 5%;
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: center;
  }

  .projects-button {
      background-color: #7DC2A5;
      border-style : solid;
      border-width: 2px;
      border-radius: 15px;
      border-color: #7DC2A5;
      margin: 5px;
      padding: 5px;
  }

  .projects-button:hover {
    background-color: #F1F1D3;
    border-style : solid;
    border-width: 2px;
    border-color: #7DC2A5;
  }
  .projects-button:hover a{
    color: #7DC2A5;
  }

  .projects-button a {
      text-decoration: none;
      color: white;
  }
    .social-links {
    height: 50%;
    margin-left: 200px;
    margin-right: 200px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    }

    .projects {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 20px;
    }
    .projects div {
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
        padding-left: 30px;
        padding-right: 30px;
        padding-bottom: 15px;
        border-radius: 15px;
        text-align: center;
    }

    .project-two {
        margin-top: 20px;
        margin-bottom: 20px;
    }


    .projects img {
        height: 250px;
    }

    .contact {
        padding-left: 120px;
        font-family: "PT Sans Caption", sans-serif;
        font-weight: 400;
        font-style: normal;
        color: #2c3e50;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
        border-radius: 15px;
        background-color: #7DC2A5;
    }

    .contact input {
        margin-bottom: 5px;
        border-radius: 10px;
        width: 80%;
        height: 20px;
    }

    #message {
        width: 80%;
        border-radius: 15px;
    }

    #envoyer {
        font-family: "PT Sans Caption", sans-serif;
        width: 20%;
        height: 30px;
        background-color: #F1F1D3;
        border-style: solid;
        border-color: #7DC2A5;

    }

    #envoyer:hover {
        background-color: #7DC2A5;
        border-style: solid;
        border-color: #F1F1D3;
        color: #F1F1D3;
    }

    .projects div:hover {
        width: 620px;
        height: 340px;
    }
    
    .return-to-top {
        height: 40px;
        width: 40px;
        background-color: #7DC2A5;
        position: fixed;
        bottom: 1%;
        right: 1%;
        border-style: solid;
        border-width: 1px;
        border-color: #fff;
    }

    .return-to-top {
        display: flex;
        justify-content: center;
    }
    .return-to-top img {
        width: 80%;
    }

    .footer {
        height: 80px;
        width: 100%;
        background-color: #F1F1D3;
        margin-top: 20px;
        position: bottom;
        padding-top: 20px;
    }

    .head {
        background-color: #7DC2A5;
        margin-bottom: 15px;
        display: flex;
        justify-content: space-between;
    }

    nav img {
        height: 3rem;
    }
</style>












