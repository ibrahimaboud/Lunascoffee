<template>
  <section-component class="bg-img" title="About" subtitle="Who we are">
    <container-component>
      <columns-component>
        <column-component>
          <h3>Our Specials</h3>
          <p>
            Stay Tuned!
          </p>
        </column-component>
        <column-component>
          <h3>Our Food</h3>
          <p>
            Coming soon!
          </p>
        </column-component>
        <column-component>
          <h3>Our History</h3>
          <p>
            Coming soon! 
          </p>
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
h3 {
  margin-bottom: 1rem;
}

.bg-img {
  background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
    url('/img/LunaLogo.jpg');
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  box-shadow: inset 0px -1px 20px 0px rgba(0, 0, 0, 0.7);
  color: #efefef;
}
</style>
