<template>
  <a class="product" :href="link">
    <div class="product-image" :style="{ backgroundImage: 'url(' + image + ')' }">
      <h3 class="product-title">
        {{ title }}
      </h3>
      <div class="product-overlay">
        <h3 class="overlay-title">
          {{ title }}
        </h3>
        <p class="overlay-info">
          {{ info }}
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
    info: {
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
    position: relative;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 4px;
    height: 100%;
    min-height: 8rem;
    overflow: hidden;
    transition: transform 0.3s ease-in-out;

    .product-title {
      opacity: 1;
      position: absolute;
      font-family: 'Montserrat', sans-serif;
      padding: 0.25rem;
      width: 100%;
      text-transform: unset;
      transition: opacity 0.3s ease-in-out;
      background-color: rgba(0, 0, 0, 0.5);
    }

    .product-overlay {
      transition: opacity 0.3s ease-in-out;
      opacity: 0;
      background-color: rgba(0, 0, 0, 0.5);
      height: 100%;
      width: 100%;
      padding: 0.25rem;

      .overlay-title {
        font-family: 'Montserrat', sans-serif;
        text-transform: unset;
      }

      .overlay-info {
        font-size: 0.8rem;
      }
    }

    &:hover {
      transform: scale(1.05);

      .product-title {
        opacity: 0;
      }

      .product-overlay {
        opacity: 1;
      }
    }
  }
}
</style>
