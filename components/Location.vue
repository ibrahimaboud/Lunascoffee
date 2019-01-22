<template>
  <section-component title="Location & Hours" subtitle="Where to find the city's most delicious food">
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
