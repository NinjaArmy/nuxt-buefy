<template>
<div id="Projects" class="container projects">
  <p class="title headline">Current Projects:</p>
  <div class="tile is-ancestor">
  <div class="tile is-parent">
    <article class="tile is-child box">
      <p class="title">Shopware 6 Theme Development</p>
      <p class="subtitle">Done</p>
        <div class="content">
          <a href="https://dampfer-store.de/" target="_blank" rel="noopener noreferrer">
            <img src="~/assets/DampferStore.png" alt="Dampfer-Store.de" />
          </a>
        </div>
    </article>
  </div>
    <div class="tile is-parent">
      <article class="tile is-child box">
        <p class="title">Nuxt.js + Buefy</p>
        <p class="subtitle">In progress</p>
        <div class="content">
          <a href="https://nuxtjs.org/" target="_blank" rel="noopener noreferrer">
            <img src="~/assets/NuxtLogo.svg" alt="Nuxt.js" />
          </a>
          <a href="https://buefy.org/" target="_blank" rel="noopener noreferrer">
            <img width="200px" src="~/assets/buefy-logo.png" alt="Buefy" />
          </a>
        </div>
      </article>
    </div>
    <div class="tile is-parent">
      <article class="tile is-child box">
        <p class="title">Shopware 6 Plugins</p>
        <p class="subtitle">Available soon</p>
        <div class="content">
          <a href="https://store.shopware.com/" target="_blank" rel="noopener noreferrer">
            <img width="200px" src="~/assets/shopware.svg" alt="shopware.com" />
          </a>
        </div>
      </article>
    </div>
  </div>

  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <article class="tile is-child box">
        <p class="title">Small Blender Projects</p>
        <p class="subtitle">Done</p>
        <div class="content">
          <img src="~/assets/Earth.png" alt="Blender" />
        </div>
      </article>
    </div>

    <div class="tile is-parent">
      <article class="tile is-child box">
        <p class="title">Shopware 6 Development</p>
        <p class="subtitle">In progress</p>
        <div class="content">
          <a href="https://meekilli.com/" target="_blank" rel="noopener noreferrer">
            <img src="~/assets/meekilli.svg" alt="meekilli.com" />
          </a>
        </div>
      </article>
    </div>

    <div class="tile is-parent">
      <article class="tile is-child box">
        <p class="title">Whats next?</p>
        <p class="subtitle">Currently working on:</p>
        <div class="content">
          <img width="200px" src="~/assets/question.jpg" alt="question" />
        </div>
      </article>
    </div>
  </div>

</div>
</template>

<script>
export default {
  name: 'Projects'
}
</script>

<style lang="scss">
.projects {
  .headline {
    padding-left: 1rem;
  }
  .content {
    text-align: center;
  }
}

</style>
