<template>
  <section-component title="Location & Hours" subtitle="Where to find the city's most delicious food">
    <container-component>
      <columns-component>
        <column-component>
          <h3>Location</h3>
          <p>1234 Green Street, San Francisco, California, 94111</p>
          <hr>
          <h3>Hours</h3>
          <p>Monday-Saturday: 10am-10pm</p>
          <p>Sunday: 11am-6pm</p>
          <hr>
          <h3>Seating & Accessibility</h3>
          <p>
            We have an wide selection of seating options, to make your dining experience unique. 
            An outdoor patio, conference room, a spacious dining area along with bar seating.
          </p>
        </column-component>
        <column-component>
          <div class="img-clipped">
            <img src="/img/city_1920-min.jpg">
          </div>
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

<style lang="scss" scoped>
img {
  width: 75%;
}

.img-clipped {
  text-align: right;
  clip-path: polygon(0 10%, 100% 0%, 100% 90%, 0 100%);
}

@media screen and (max-width: 768px) {
  .img-clipped {
    display: none;
  }
}
</style>
