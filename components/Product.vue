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
  color: #fff;
  text-decoration: none;
  transition: color 0.2s;

  .product-image {
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 4px;
    max-height: 100%;
    min-height: 8rem;
    transition: transform 0.2s;
    overflow: hidden;

    &:hover {
      transform: scale(1.05);
    }

    .product-title {
      font-family: 'Montserrat', sans-serif;
      background-color: rgba(1, 1, 1, 0.5);
      transition: background-color 0.2s;
      padding: 0.25rem 0 0 0.25rem;
    }
  }

  &:hover,
  &:active {
    color: rgb(207, 25, 25);

    .product-title {
      background-color: rgba(1, 1, 1, 0.6);
    }
  }
}
</style>
