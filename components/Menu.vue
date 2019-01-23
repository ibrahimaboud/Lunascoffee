<template>
  <section-component title="Menu" subtitle="Our most delicious options">
    <container-component>
      <columns-component>
        <column-component>
          <product-component title="Steaks" info="Bicycle rights meditation trust fund consequat disrupt, try-hard tbh intelligentsia vape." image="/img/steak_2_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Burgers" info="Freegan blog kickstarter migas reprehenderit flannel irure artisan ad iPhone etsy consequat." image="/img/burger_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Wings" info="Yuccie cardigan trust fund mumblecore hashtag retro nostrud venmo in excepteur." image="/img/wings_1920-min.jpg" />
        </column-component>
      </columns-component>
      <columns-component>
        <column-component>
          <product-component title="Salads" info="Fixie tote bag in aute. Art party offal artisan chicharrones keffiyeh." image="/img/salad_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Tacos" info="Fixie affogato hot chicken palo santo ethical VHS plaid umami, whatever jean shorts marfa everyday carry labore." image="/img/tacos_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Beers" info="Labore nostrud prism farm-to-table officia." image="/img/beer_1920-min.jpg" />
        </column-component>
        <column-component>
          <product-component title="Desserts" info="Drinking vinegar cred vinyl venmo exercitation flexitarian, irure pickled quinoa aliquip." image="/img/dessert_1920-min.jpg" />
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
