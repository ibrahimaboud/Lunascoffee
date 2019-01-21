<template>
  <main>
    <navbar />
    <hero />
  </main>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Hero from '~/components/Hero.vue'

export default {
  components: {
    Navbar,
    Hero
  }
}
</script>
