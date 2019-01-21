<template>
  <main>
    <Navbar />
    <Hero />
    <Container>
      <OurMenu />
    </Container>
  </main>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Hero from '~/components/Hero.vue'
import OurMenu from '~/components/Menu.vue'
import Container from '~/components/base/Container.vue'

export default {
  components: {
    Navbar,
    Hero,
    OurMenu,
    Container
  }
}
</script>
