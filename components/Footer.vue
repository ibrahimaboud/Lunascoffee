<template>
  <footer class="footer">
    <container-component>
      <p class="text-centered">
        &copy; 2020 
        <a class="footer-link" href="https://github.com/hemo650">
          Ibrahim Aboudamous.
        </a>
      </p>
      <p class="text-centered">
        Order food and drinks from here
        <a class="footer-link" href="https://www.doordash.com/store/luna-s-coffee-house-san-francisco-220139/en-US">
            Doordash. 
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
