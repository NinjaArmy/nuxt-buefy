<template>
  <div class="container about-me">
    <div class="card">
    <div class="card-content">
      <div class="media" style="margin-bottom: 0">
        <div class="media-left">
          <figure class="image is-128x128">
            <img src="~/assets/joschi.jpg" alt="Joschi" />
          </figure>
        </div>
        <div class="media-content">
          <p class="title is-4">Joschi Mehta</p>
          <p class="subtitle is-5">I love to create some awesome apps for Shopware 6 or with Nuxt.js. I also know some other technologies and I'm very deep into E-Commerce. I guess that's my biggest passion.
          </p>
        </div>
      </div>

    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutMe'
}
</script>

<style lang="scss" scoped>
$tablet: 768px;

.about-me {
  .card {
    box-shadow: none;
  }
  .media {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

  }

}

@media screen and (min-width: $tablet) {
  .about-me {
    .media {
      display: flex;
      flex-direction: row;
      justify-content: flex-start;
      align-items: flex-start;

    }
  }
}
</style>
