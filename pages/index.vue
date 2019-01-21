<template>
  <main>
    <Navbar />
    <Hero />
    <OurMenu />
  </main>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Hero from '~/components/Hero.vue'
import OurMenu from '~/components/Menu.vue'

export default {
  components: {
    Navbar,
    Hero,
    OurMenu
  }
}
</script>
