<template>
  <section class="section">
    <Introduction/>
    <AboutMe/>
    <Projects/>
    <Outro/>
    <CarouselList/>
  </section>
</template>

<script>
import Introduction from '@/components/Introduction';
import AboutMe from '@/components/AboutMe';
import Projects from '@/components/Projects';
import Outro from '@/components/Outro';
import CarouselList from '@/components/CarouselList';

export default {
  name: 'HomePage',

  components: {
    Introduction,
    AboutMe,
    Projects,
    Outro,
    CarouselList
  }
}
</script>
