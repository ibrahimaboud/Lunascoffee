<template>
  <main>
    <NavbarComponent />
    <HeroComponent />
    <SectionComponent>
      <ContainerComponent>
        <MenuComponent />
      </ContainerComponent>
    </SectionComponent>
  </main>
</template>

<script>
import NavbarComponent from '~/components/Navbar.vue'
import HeroComponent from '~/components/Hero.vue'
import MenuComponent from '~/components/Menu.vue'
import SectionComponent from '~/components/base/Section.vue'
import ContainerComponent from '~/components/base/Container.vue'

export default {
  components: {
    NavbarComponent,
    HeroComponent,
    MenuComponent,
    ContainerComponent,
    SectionComponent
  }
}
</script>
