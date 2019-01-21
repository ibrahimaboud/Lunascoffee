<template>
  <section class="section">
    <slot />
  </section>
</template>

<style lang="scss" scoped>
.section {
  padding-top: 3rem;

  &:nth-child(even) {
    background-color: #ffffff;
  }

  &:nth-child(odd) {
    background-color: #efefef;
  }
}
</style>
