<template>
  <section-component title="Location & Hours" subtitle="Where to find the city's most delicious food">
    <container-component>
      <columns-component>
        <column-component>
          <p>Text</p>
        </column-component>
        <column-component>
          <img src="/img/city_1920-min.jpg">
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

export default {
  components: {
    ContainerComponent,
    SectionComponent,
    ColumnsComponent,
    ColumnComponent
  }
}
</script>
