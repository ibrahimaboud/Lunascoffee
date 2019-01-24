<template>
  <main>
    <navbar-component />
    <hero-component id="home" title="George's" subtitle="The best San Francisco has to offer." info="Located right off of The Embarcadero." />
    <menu-component id="menu" />
    <location-component id="hours_location" />
  </main>
</template>

<script>
import NavbarComponent from '~/components/Navbar.vue'
import HeroComponent from '~/components/Hero.vue'
import MenuComponent from '~/components/Menu.vue'
import LocationComponent from '~/components/Location.vue'

export default {
  components: {
    NavbarComponent,
    HeroComponent,
    MenuComponent,
    LocationComponent
  }
}
</script>
