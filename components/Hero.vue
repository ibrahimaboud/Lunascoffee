<template>
  <header class="hero">
    <div class="box">
      <h1>George's</h1>
      <h2>The best San Francisco has to offer.</h2>
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
  color: #efefef;
  height: 50vh;

  .box {
    display: block;
    width: 80vw;
    padding: 3rem;
    margin: 0 auto;
  }
}
</style>
