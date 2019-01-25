<template>
  <footer class="footer">
    <container-component>
      <p class="text-centered">
        &copy; 2019 
        <a class="footer-link" href="https://github.com/georgebutler">
          George Butler.
        </a>
      </p>
      <p class="text-centered">
        Images and media sourced from 
        <a class="footer-link" href="https://pixabay.com/">
          Pixabay.
        </a>
      </p>
    </container-component>
  </footer>
</template>

<script>
import ContainerComponent from '~/components/base/Container.vue'

export default {
  components: {
    ContainerComponent
  }
}
</script>

<style lang="scss" scoped>
.footer {
  padding-bottom: 2rem;
  padding-top: 2rem;
}

.text-centered {
  text-align: center;
}

.footer-link {
  font-weight: 600;
}
</style>
