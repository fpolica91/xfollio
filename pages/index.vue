<template>
  <!-- Content -->
  <div class="content">
    <!-- Profile -->
    <img class="content__profile" src="/img/profile.jpeg" />
    <article class="content__article content__article--center content__article--margin-16">
      <p class="content__article-title content__article-title--large">Fabricio Policarpo</p>
      <p class="content__article-subtitle">FullStack Developer based in Palm Beach</p>
      <p class="content__article-links">
        <a href="/docs/developer.pdf" target="_blank">
          <i class="far fa-file-alt content__article-link" />
        </a>
        <a href="https://github.com/fpolica91" target="_blank">
          <i class="fab fa-github content__article-link" />
        </a>
        <a href="https://linkedin.com/in/fpolica" target="_blank">
          <i class="fab fa-linkedin-in content__article-link" />
        </a>
        <a href="https://twitter.com/Fabrici47288647" target="_blank">
          <i class="fab fa-twitter content__article-link" />
        </a>
        <a href="mailto:fabriciopolicarpo0@gmail.com" target="_blank">
          <i class="far fa-envelope content__article-link" />
        </a>
      </p>
    </article>

    <!-- About Me -->
    <article class="content__article content__article--margin-16">
      <p class="content__article-details">
        I am a fullstack developer with experience working with front end application layers,
        databases, mobile applications and server technologies. Currently working with
        <a
          href="https://nuxtjs.org/"
          target="_blank"
        >NuxtJS</a> , and serverless technolgies using
        <a
          href="https://firebase.google.com"
          target="_blank"
        >Google Cloud</a>
        <br />
        <br />I am skilled working with React for web and mobile, VueJS, Typescript and Material Design Principles, and
        NodeJS, Postgres, MongoDB, Firestore.
        <br />
        <br />I am comfortable working with a Software as a Service business model and have working knowledge of
        TDD, DDD, and SOLID.
        <br />
        <br />
        <a href="mailto:fabriciopolicarpo0@gmail.com" target="_blank">Contact Me!</a> I am opened to new opportunites
        to grow my skillset and contribute to a great team to deliver a great product
      </p>
    </article>

    <!-- Projects -->
    <article class="content__article content__article--margin-24">
      <p class="content__article-title content__article-title--medium">
        <i class="fa fa-briefcase" /> Projects
      </p>
      <hr />
    </article>

    <!-- Project -->
    <article class="content__article content__article--margin-8">
      <!-- Title -->
      <p class="content__article-title content__article-title">TriShare</p>

      <!-- Details -->
      <p class="content__article-details content__article--margin-8">
        Application that allows the upload of equirectangular images, to create an immersive experience.
        <br />
        <span class="content__article-metadata">
          <b>
            <i class="fa fa-code" /> Technology:
          </b> Three.js, React, NodeJS, MongoDB, Socket.io, Styled Components.
        </span>
      </p>›
      <!-- Preview -->
      <a href="https://trishare.herokuapp.com/" target="_blank">
        <img src="/img/trishare.png" class="content__article-preview" />
      </a>

      <!-- Links -->
      <p class="content__article-details">
        --
        <br />
        <a href="#" target="_blank">Demo</a> |
        <a href="https://github.com/fpolica91/VRFrontEnd" target="_blank">View on Github</a>
      </p>
      <hr />
    </article>

    <!-- Project -->
    <article class="content__article content__article--margin-8">
      <!-- Title -->
      <p class="content__article-title content__article-title">Codey</p>

      <!-- Details -->
      <p class="content__article-details content__article--margin-8">
        Multi user chatroom with simple built in Javascript compiler.
        <br />
        <span class="content__article-metadata">
          <b>
            <i class="fa fa-code" /> Technology:
          </b> NodeJS, Express, Socket.io, HBS, MongoDB
        </span>
      </p>›
      <!-- Preview -->
      <a href="https://thecodey.herokuapp.com/" target="_blank">
        <img src="/img/codey.png" class="content__article-preview" />
      </a>

      <!-- Links -->
      <p class="content__article-details">
        --
        <br />
        <a href="#" target="_blank">Demo</a> |
        <a href="https://github.com/JesusGarcia23/codey" target="_blank">View on Github</a>
      </p>
      <hr />
    </article>
  </div>
</template>

<style>
/* Block Elements */
.content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  z-index: 4;
}
.content__profile {
  height: 180px;
  width: 180px;
  border: solid white 4px;
  border-radius: 50%;
  box-shadow: 2px 2px 8px #494b4b;
}
.content__article {
  width: 100%;
}
.content__article-title {
  font-size: 22px;
  font-weight: bold;
  color: #3a4145;
}
.content__article-subtitle {
  font-size: 22px;
  font-weight: bold;
  color: #a9a9a9;
}
.content__article-details {
  font-size: 16px;
}
.content__article-metadata {
  font-size: 13px;
}
.content__article-links {
  margin: 8px 0;
}
.content__article-link {
  font-size: 22px;
  margin: 0 8px;
}
.content__article-preview {
  width: 100%;
  max-width: 800px;
  margin-top: 16px;
}

/* Modifiers */
.content__article-title--medium {
  font-size: 32px;
  font-weight: bold;
}
.content__article-title--large {
  font-size: 40px;
  font-weight: bold;
}
.content__article--center {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.content__article--margin-8 {
  margin-top: 8px;
}
.content__article--margin-16 {
  margin-top: 16px;
}
.content__article--margin-24 {
  margin-top: 24px;
}

@media only screen and (min-width: 800px) {
  .content {
    width: 800px;
  }
}
</style>
