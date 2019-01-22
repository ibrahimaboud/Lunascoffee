<template>
  <SectionComponent title="Menu" subtitle="Our most delicious options">
    <ContainerComponent>
      <ColumnsComponent>
        <ColumnComponent>
          <ProductComponent title="Steaks" image="/img/steak_2_1920-min.jpg" />
        </ColumnComponent>
        <ColumnComponent>
          <ProductComponent title="Burgers" image="/img/burger_1920-min.jpg" />
        </ColumnComponent>
        <ColumnComponent>
          <ProductComponent title="Wings" image="/img/wings_1920-min.jpg" />
        </ColumnComponent>
      </ColumnsComponent>
      <ColumnsComponent>
        <ColumnComponent>
          <ProductComponent title="Salads" image="/img/salad_1920.jpg" />
        </ColumnComponent>
        <ColumnComponent>
          <ProductComponent title="Tacos" image="/img/tacos_1920.jpg" />
        </ColumnComponent>
        <ColumnComponent>
          <ProductComponent title="Beers" image="/img/beer_1920-min.jpg" />
        </ColumnComponent>
        <ColumnComponent>
          <ProductComponent title="Desserts" image="/img/dessert_1920.jpg" />
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
import ProductComponent from '~/components/Product.vue'

export default {
  components: {
    ContainerComponent,
    SectionComponent,
    ColumnsComponent,
    ColumnComponent,
    ProductComponent
  }
}
</script>
