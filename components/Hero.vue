<template>
  <header class="hero">
    <container-component>
      <div class="box">
        <h1 class="title">
          {{ title }}
        </h1>
        <h2 class="subtitle">
          {{ subtitle }}
        </h2>
        <h3 class="info">
          {{ info }}
        </h3>
      </div>
    </container-component>
  </header>    
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
    info: {
      type: String,
      default: ''
    }
  }
}
</script>


<style lang="scss" scoped>
.hero {
  background-color: #111;
  background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
    url('/img/steak_1920.jpg');
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  box-shadow: inset 0px -1px 20px 0px rgba(0, 0, 0, 0.7);
  color: #ffffff;
  min-height: 25vh;

  .box {
    padding-top: 6rem;

    .info {
      font-family: 'Montserrat', sans-serif;
      text-transform: unset;
      padding-top: 3rem;
      padding-bottom: 3rem;
    }
  }
}
</style>
