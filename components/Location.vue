<template>
  <section-component title="Location & Hours">
    <container-component>
      <p>Text</p>
    </container-component>
  </section-component>
</template>

<script>
import ContainerComponent from '~/components/base/Container.vue'
import SectionComponent from '~/components/base/Section.vue'

export default {
  components: {
    ContainerComponent,
    SectionComponent
  }
}
</script>
