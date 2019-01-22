<template>
  <div class="column">
    <slot />
  </div>    
</template>

<style lang="scss" scoped>
.column {
  flex: 1;

  &:not(:last-child) {
    margin: 0 1rem 0 0;
  }
}

@media (max-width: 400px) {
  .column {
    &:not(:last-child) {
      margin: 0 0 1rem 0;
    }
  }
}
</style>
