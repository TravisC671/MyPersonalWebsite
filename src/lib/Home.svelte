<script>
</script>

<div class="home-wrapper">
  <div class="title-wrapper">
    <h3 class="pretitle title">Hello! I'm</h3>
    <h1 class="name-title title primary-title">Travis</h1>
    <h1 class="name-title title secondary-title">Calhoun</h1>
  </div>
  <div class="button-wrapper">
    <div class="gradient-module-wrapper about-me-button-gradient"><button class="about-me-button">About Me</button></div>
    <div class="gradient-module-wrapper projects-button-gradient"><button class="projects-button">Projects</button></div>
    <div class="gradient-module-wrapper achievements-button-gradient"><button class="achievements-button">Achievements</button></div>
  </div>
</div>

<style>
  .home-wrapper {
    display: flex;
    flex-direction: column;
    width: 100vw;
  }

  .title-wrapper {
    width: 100vw;
    height: fit-content;
  }

  .title {
    font-family: "articulat-heavy-cf", sans-serif;
    font-weight: 900;
    font-style: italic;
  }

  .pretitle {
    color: #ababab;
    font-size: 2.5625rem;
    margin-bottom: 40px;
    margin-left: 20vw;
  }

  .name-title {
    font-size: 6.25rem;
    margin: 0px;
  }

  .primary-title {
    color: #4cdea4;
    margin-left: 25vw;
    line-height: .6;
  }

  .secondary-title {
    position: relative;
    color: #1ad0b4;
    margin-left: 30vw;
  }

  .button-wrapper {

  }

  .gradient-module-wrapper {
    position: relative;
    padding: 5px;
    border-radius: 25px;
    width: fit-content;
    transition: .2s;
  }

  .about-me-button-gradient {
    background: linear-gradient(to right, #4cdea4, #149f8a);
  }
  
  /*this is ugly*/
  .about-me-button-gradient:hover {
    background: linear-gradient(to left, #4cdea4, #149f8a);
  }
  .about-me-button-gradient:hover > .about-me-button {
    background: #00000000;
  }



  .projects-button-gradient {
    background: linear-gradient(to right, #dfac4d, #d647a6);
  }


  .projects-button-gradient:hover {
    background: linear-gradient(to left, #dfac4d, #d647a6);
  }
  .projects-button-gradient:hover > .projects-button {
    background: #00000000;
  }

  .achievements-button-gradient {
    background: linear-gradient(to right, #31bfdf, #6f6bd6);
  }


  .achievements-button-gradient:hover {
    background: linear-gradient(to left, #31bfdf, #6f6bd6);
  }
  .achievements-button-gradient:hover > .achievements-button {
    background: #00000000;
  }
</style>