<template>
  <main>
    <navbar-component />
    <hero-component title="George's" subtitle="The best San Francisco has to offer." info="Located right off of the Embarcadero." />
    <menu-component />
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
