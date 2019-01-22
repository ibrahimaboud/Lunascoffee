<template>
  <section class="section">
    <container-component>
      <h2 class="section-title">
        {{ title }}
      </h2>
      <h3 class="section-subtitle">
        {{ subtitle }}
      </h3>
    </container-component>
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
  padding-bottom: 5rem;

  &:nth-child(even) {
    background-color: #ffffff;
  }

  &:nth-child(odd) {
    background-color: #efefef;
  }

  .section-subtitle {
    font-family: 'Montserrat', sans-serif;
    text-transform: unset;
    padding-bottom: 2rem;
  }
}
</style>
