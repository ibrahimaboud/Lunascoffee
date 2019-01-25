<template>
  <section-component title="Menu" subtitle="Our most delicious options">
    <container-component>
      <columns-component>
        <column-component>
          <product-component title="Steaks" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/steak_2_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Burgers" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/burger_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Wings" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/wings_1920-min.jpg" />
        </column-component>
      </columns-component>
      <columns-component>
        <column-component>
          <product-component title="Salads" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/salad_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Tacos" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/tacos_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Beers" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/beer_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Desserts" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/dessert_1920-min.jpg" />
        </column-component>
      </columns-component>
    </container-component>
  </section-component>
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
