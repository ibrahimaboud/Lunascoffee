<template>
  <section class="section">
    <ContainerComponent>
      <h2 class="section-title">
        {{ title }}
      </h2>
      <h3 class="section-subtitle">
        {{ subtitle }}
      </h3>
    </ContainerComponent>
    <slot />
  </section>
</template>

<script>
import ContainerComponent from '~/components/base/Container.vue'

export default {
  components: {
    ContainerComponent
  },
  props: {
    title: {
      type: String,
      default: ''
    },
    subtitle: {
      type: String,
      default: ''
    }
  }
}
</script>


<style lang="scss" scoped>
.section {
  padding-top: 3rem;
  padding-bottom: 3rem;

  &:nth-child(even) {
    background-color: #ffffff;
  }

  &:nth-child(odd) {
    background-color: #efefef;
  }

  .section-subtitle {
    padding-bottom: 2rem;
  }
}
</style>
