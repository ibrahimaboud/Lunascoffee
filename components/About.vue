<template>
  <section-component class="bg-img" title="About" subtitle="Who we are">
    <container-component>
      <columns-component>
        <column-component>
          <h3>Our Staff</h3>
          <hr>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
            Phasellus et rhoncus mi. 
            Praesent vel nisl tempus, mattis leo id, eleifend augue. 
            Phasellus sit amet velit varius, vestibulum purus et, interdum lorem. 
            Phasellus fringilla eget nisi sed vulputate. 
          </p>
        </column-component>
        <column-component>
          <h3>Our Food</h3>
          <hr>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
            Phasellus et rhoncus mi. 
            Praesent vel nisl tempus, mattis leo id, eleifend augue. 
            Phasellus sit amet velit varius, vestibulum purus et, interdum lorem. 
            Phasellus fringilla eget nisi sed vulputate. 
          </p>
        </column-component>
        <column-component>
          <h3>Our History</h3>
          <hr>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
            Phasellus et rhoncus mi. 
            Praesent vel nisl tempus, mattis leo id, eleifend augue. 
            Phasellus sit amet velit varius, vestibulum purus et, interdum lorem. 
            Phasellus fringilla eget nisi sed vulputate. 
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
.bg-img {
  background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
    url('/img/kitchen_1920-min.jpg');
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  box-shadow: inset 0px -1px 20px 0px rgba(0, 0, 0, 0.7);
  color: #efefef;
}
</style>
