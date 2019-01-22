<template>
  <a class="product" :href="link">
    <div class="product-image" :style="{ backgroundImage: 'url(' + image + ')' }">
      <h3 class="product-title">
        {{ title }}
      </h3>
    </div>
  </a>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: ''
    },
    image: {
      type: String,
      default: ''
    },
    link: {
      type: String,
      default: '#'
    }
  }
}
</script>

<style lang="scss" scoped>
.product {
  text-decoration: none;
  color: #fff;
  transition: color 0.2s;

  .product-image {
    border-radius: 2px;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;

    transition: transform 0.2s;

    min-height: 8rem;
    max-height: 100%;

    &:hover {
      transform: scale(1.5);
    }
  }

  &:hover {
    color: #eee;
  }
}
</style>
