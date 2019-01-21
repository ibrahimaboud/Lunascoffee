<template>
  <div class="columns">
    <slot />
  </div>    
</template>

<style lang="scss" scoped>
.columns {
  display: flex;
}

@media (max-width: 400px) {
  .columns {
    display: block;
  }
}
</style>
