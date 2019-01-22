<template>
  <div class="column">
    <slot />
  </div>    
</template>

<style lang="scss" scoped>
.column {
  flex: 1;

  &:not(:last-child) {
    margin-right: 1rem;
  }
}
</style>
