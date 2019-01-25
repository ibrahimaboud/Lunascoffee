<template>
  <div>
    <nuxt />
  </div>
</template>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

html,
body {
  background-color: #fff;
  color: #111;
  font-family: 'Aleo', serif;
  font-size: 18px;
  font-weight: 300;
  text-rendering: optimizeLegibility;
  overflow-x: hidden;
}

h1,
h2,
h3 {
  font-weight: 300;
  text-transform: uppercase;
  margin-bottom: 0.5rem;
}

h1 {
  font-size: 3rem;
  word-spacing: 0.32rem;
  letter-spacing: 0.16rem;
}

h2 {
  font-size: 2rem;
}

a {
  color: #111;
  text-decoration: none;
  padding: 1rem auto;
  transition: color 0.3s ease-in-out;
  color: rgb(153, 19, 19);
  font-weight: 600;

  &:hover,
  &:active {
    color: rgb(207, 25, 25);
  }
}

p {
  font-family: 'Montserrat', sans-serif;
}

img {
  width: 100%;
  border-radius: 2px;
}

hr {
  border-style: none;
  margin: 1rem 0 1rem 0;
}
</style>
