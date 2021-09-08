<template>
  <section class="container brandSlider">
    <b-carousel-list
      v-model="values"
      :data="items"
      :arrow="arrow"
      :arrow-hover="arrowHover"
      :items-to-show="perList"
      :items-to-list="increment"
      :repeat="repeat"
      :has-drag="drag"
      :has-grayscale="gray"
      :has-opacity="opacity" />
  </section>
</template>

<script>
export default {
  data() {
    return {
      arrow: true,
      arrowHover: false,
      drag: true,
      gray: false,
      opacity: false,
      values: 1,
      perList: 6,
      increment: 1,
      repeat: true,
      autoplay: false,
      items: [
        {
          title: 'Wordpress',
          image: require('../assets/WordPress.png')
        },
        {
          title: 'Nuxt.js',
          image:  require('../assets/NuxtLogo.svg')
        },
        {
          title: 'Shopware',
          image:  require('../assets/shopware.svg')
        },
        {
          title: 'Vue.js',
          image: require('../assets/Vue.svg')
        },
        {
          title: 'Buefy',
          image: require('../assets/buefy-logo.png')
        },
        {
          title: 'Docker',
          image: require('../assets/Docker.svg')
        },
        {
          title: 'HTML5',
          image: require('../assets/HTML5.svg')
        },
        {
          title: 'Sass',
          image: require('../assets/Sass.svg')
        },
        {
          title: 'Blender',
          image: require('../assets/Blender.svg')
        },
        {
          title: 'CSS3',
          image: require('../assets/CSS3.svg')
        },
      ]
    }
  }
}
</script>

<style lang="scss">

.brandSlider {

  padding: 1.5rem 0;

  .has-shadow {
    box-shadow: none;
  }


  .carousel-slide {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  img {
    width: 150px;
    height: auto;
  }

}


</style>
