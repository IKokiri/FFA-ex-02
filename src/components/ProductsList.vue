<template>
  <div>
       <ul>
            <ProductItem/>
       </ul>
  </div>

</template>

<script>
import ProductItem from './ProductItem.vue'

export default {
  name: 'ProductsList',
    components: {
    ProductItem
  },
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 p {
        width: 20%;
        display: inline-block;
       
    }
</style>