<template>
  <SectionComponent>
    <ContainerComponent>
      <h2>Menu</h2>
      <ColumnsComponent>
        <ColumnComponent>
          <div class="menu-box">
            <h3>Product</h3>
          </div>
        </ColumnComponent>
        <ColumnComponent>
          <div class="menu-box">
            <h3>Product</h3>
          </div>
        </ColumnComponent>
        <ColumnComponent>
          <div class="menu-box">
            <h3>Product</h3>
          </div>
        </ColumnComponent>
        <ColumnComponent>
          <div class="menu-box">
            <h3>Product</h3>
          </div>
        </ColumnComponent>
      </ColumnsComponent>
    </ContainerComponent>
  </SectionComponent>
</template>

<script>
import ContainerComponent from '~/components/base/Container.vue'
import SectionComponent from '~/components/base/Section.vue'
import ColumnsComponent from '~/components/base/Columns.vue'
import ColumnComponent from '~/components/base/Column.vue'

export default {
  components: {
    ContainerComponent,
    SectionComponent,
    ColumnsComponent,
    ColumnComponent
  }
}
</script>

<style lang="scss" scoped>
.menu-box {
  background: rgb(255, 197, 197);
}
</style>
