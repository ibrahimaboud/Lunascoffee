<template>
  <main>
    <NavbarComponent />
    <HeroComponent />
    <MenuComponent />
  </main>
</template>

<script>
import NavbarComponent from '~/components/Navbar.vue'
import HeroComponent from '~/components/Hero.vue'
import MenuComponent from '~/components/Menu.vue'

export default {
  components: {
    NavbarComponent,
    HeroComponent,
    MenuComponent
  }
}
</script>
