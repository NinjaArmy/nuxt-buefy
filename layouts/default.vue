<template>
  <div>
    <Navbar/>
    <Nuxt/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar'
import Footer from '@/components/Footer'

export default {
  components: {  Footer,  Navbar },
  data () {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' }
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: { name: 'inspire' }
        }
      ]
    }
  }
}
</script>
