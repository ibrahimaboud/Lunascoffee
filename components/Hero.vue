<template>
  <header class="hero">
    <div class="box">
      <h1 class="title">
        George's
      </h1>
      <h2 class="subtitle">
        The best San Francisco has to offer.
      </h2>
    </div>
  </header>    
</template>

<style lang="scss" scoped>
.hero {
  background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
    url('/img/steak_1920.jpg');
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  box-shadow: inset 0px -1px 20px 0px rgba(0, 0, 0, 0.7);
  color: #efefef;
  height: 50vh;
  min-height: 20rem;

  .box {
    display: block;
    width: 80vw;
    height: 100%;
    margin: 0 auto;

    .title {
      padding-top: 6rem;
    }
  }
}
</style>
