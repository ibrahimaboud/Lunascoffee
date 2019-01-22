<template>
  <main>
    <NavbarComponent />
    <HeroComponent title="George's" subtitle="The best San Francisco has to offer." info="Located right off of the Embarcadero." />
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
