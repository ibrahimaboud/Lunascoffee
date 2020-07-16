<template>
  <section-component title="Location & Hours" subtitle="Where to find the city's most delicious food">
    <container-component>
      <columns-component>
        <column-component>
          <h3>Location</h3>
          <p>1101 Potrero Ave, San Francisco, California, 94111</p>
          <hr>
          <h3>Hours</h3>
          <p>Monday-Friday: 7am-3pm</p>
          <hr>
          <h3>Seating & Accessibility</h3>
          <p>
            We are currently respecting social distancing guideline and require everything to be curb side pick
          </p>
        </column-component>
        <column-component>
          <div class="img-clipped">
            <img src="/img/lunaoutside.jpg">
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
  clip-path: polygon(0 5%, 100% 0%, 100% 95%, 0 100%);
}

@media screen and (max-width: 768px) {
  .img-clipped {
    display: none;
  }
}
</style>
