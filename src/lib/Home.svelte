<script>
  import Travis from "./Home/Travis.svelte";
  import Calhoun from "./Home/Calhoun.svelte";
</script>

<div class="home-wrapper">
  <div class="title-wrapper">
    <h3 class="pretitle title">Hello! I'm</h3>
    <h1 class="name-title title primary-title">
      <Travis width={20} height={6} />
    </h1>

    <h1 class="name-title title secondary-title">
      <Calhoun width={26} height={6} />
    </h1>
  </div>
  <div class="button-wrapper">
    <div class="gradient-module-wrapper about-me-button-gradient">
      <button class="about-me-button">About Me</button>
    </div>
    <div class="gradient-module-wrapper projects-button-gradient">
      <button class="projects-button">Projects</button>
    </div>
    <div class="gradient-module-wrapper achievements-button-gradient">
      <button class="achievements-button">Achievements</button>
    </div>
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
    line-height: 0.6;
  }

  .secondary-title {
    position: relative;
    color: #1ad0b4;
    margin-left: 30vw;
  }

  .button-wrapper {
    display: flex;
    gap: 20px;
    margin-left: 32vw;
    margin-top: 8vh;
  }

  .gradient-module-wrapper {
    position: relative;
    padding: 5px;
    border-radius: 25px;
    width: fit-content;
    transition: 0.2s;
  }

  /* about me button */
  .about-me-button {
    color: #6fec6c;
    transition: 0.2s;
  }

  .about-me-button-gradient {
    background: #4cdea4;
    background: linear-gradient(90deg, #4cdea4, #91f934);
  }

  .about-me-button-gradient:hover {
    background: #4cdea4;
    background: linear-gradient(90deg, #4cdea4, #91f934);
  }
  .about-me-button-gradient:hover > .about-me-button {
    background: #00000000;
    color: var(--background);
    letter-spacing: 1px;
  }

  /* projects button */

  .projects-button {
    color: #eb5a68;
    transition: 0.2s;
  }

  .projects-button-gradient {
    background: #e73c7e;
    background: linear-gradient(90deg, #e73c7e 0%, #ee7752 100%);
  }

  .projects-button-gradient:hover {
    background: linear-gradient(90deg, #e73c7e 0%, #ee7752 100%);
  }

  .projects-button-gradient:hover > .projects-button {
    background: #00000000;
    color: rgb(255, 255, 255);
    letter-spacing: 1px;
  }

  /* achievements button */
  .achievements-button {
    color: #4f97db;
    transition: 0.2s;
  }

  .achievements-button-gradient {
    background: linear-gradient(to right, #31bfdf, #6f6bd6);
  }

  .achievements-button-gradient:hover {
    background: linear-gradient(to left, #31bfdf, #6f6bd6);
  }
  .achievements-button-gradient:hover > .achievements-button {
    background: #00000000;
    color: var(--background);
    letter-spacing: 2px;
  }
</style>
