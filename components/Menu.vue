<template>
  <section-component title="Recommended" subtitle="Our most delicious options">
    <container-component>
      <columns-component>
        <column-component>
          <product-component title="Breakfast" info="Our best breakfasts come with your choice of meat, cheese, and eggs,on a bagel or crossiant." image="/img/bagel.jpg" />
        </column-component>
        <column-component>
          <product-component title="Sandwhich" info="Our most popular sandwhich comes on either a French Roll or Ductch Crunch Roll toasted to your perfection with Chicekn Teriyaki, lettuce, tomatos." image="/img/sandwhichluna.jpg" />
        </column-component>
        <column-component>
          <product-component title="Plates" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/chickenplate.jpg" />
        </column-component>
      </columns-component>
      <columns-component>
        <column-component>
          <product-component title="Coffee" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/coffeel.jpg" />
        </column-component>
        <column-component>
          <product-component title="Smoothies" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/smoothie.jpg" />
        </column-component>
        <column-component>
          <product-component title="Orange Juice" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/OJ.jpg" />
        </column-component>
        <column-component>
          <product-component title="Vegetarian" info="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vel nisl tempus, mattis leo id, eleifend augue." image="/img/veggie.jpg" />
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
