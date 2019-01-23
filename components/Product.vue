<template>
  <a class="product" :href="link">
    <div class="product-image" :style="{ backgroundImage: 'url(' + image + ')' }">
      <div class="product-overlay">
        <h3 class="product-title">
          {{ title }}
        </h3>
        <p class="product-info">
          This is some info about the product. It's not much but it's text.
        </p>
      </div>
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
  transition: color 0.3s ease-in-out;

  .product-image {
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 4px;
    height: 100%;
    min-height: 8rem;
    overflow: hidden;
    transition: transform 0.3s ease-in-out;

    .product-overlay {
      transition: transform 0.3s ease-in-out;
      transform: translateY(-100%);
      background-color: rgba(0, 0, 0, 0.5);
      height: 100%;
      width: 100%;
    }

    .product-title {
      font-family: 'Montserrat', sans-serif;
      padding: 0.25rem 0 0 0.25rem;
      text-transform: unset;
    }

    .product-info {
      padding: 0.25rem 0 0 0.25rem;
      font-size: 0.8rem;
    }

    &:hover {
      transform: scale(1.05);

      .product-overlay {
        transform: translateY(0);
      }
    }
  }
}
</style>
