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
    },
    background: {
      type: String,
      default: null
    }
  }
}
</script>


<style lang="scss" scoped>
.section {
  padding-bottom: 5rem;
  padding-top: 3rem;
  clip-path: polygon(0 5%, 100% 0, 100% 95%, 0 100%);

  &:first-of-type {
    clip-path: polygon(0 0, 100% 0, 100% 95%, 0 100%);
  }

  &:last-of-type {
    clip-path: polygon(0 5%, 100% 0, 100% 100%, 0 100%);
  }

  &:nth-child(even) {
    background-color: #ffffff;
  }

  &:nth-child(odd) {
    background-color: #efefef;
  }

  .section-subtitle {
    font-family: 'Montserrat', sans-serif;
    padding-bottom: 2rem;
    text-transform: unset;
  }
}
</style>
