<template>
  <div>
    <nuxt />
  </div>
</template>

<style>
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
