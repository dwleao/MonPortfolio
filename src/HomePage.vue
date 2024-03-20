<template>
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=PT+Sans+Caption:wght@400;700&display=swap" rel="stylesheet">
    </head>
    <body>
        

  <div class="main-container">
      <div class="container-one">
          <div class="profile">
              <img src="./assets/pp.jpg" alt="">
              <h3>Kevin LEAO</h3>
              <p>Développeur Web</p>
          </div>
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
                  <a href="">Mes Projets</a>
              </div>
              <div class="projects-button">
                  <a href="">Me Contacter</a>
              </div>
          </div>
      </div>
  </div>    
  </body>
  <footer>

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
    display: flex;
    flex-direction: column;
    justify-content: space-around;


    }

</style>












<!-- <template>
  <MainCard/>
</template>

<script>
import MainCard from './components/MainCard.vue';
export default {
  name: 'App',
  components: {
    MainCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>-->

color: #2c3e50;