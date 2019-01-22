<template>
  <div class="columns">
    <slot />
  </div>    
</template>

<style lang="scss" scoped>
.columns {
  display: flex;

  &:not(:first-child) {
    margin: 1rem 0 0 0;
  }
}

@media (max-width: 768px) {
  .columns {
    display: block;
  }
}
</style>
