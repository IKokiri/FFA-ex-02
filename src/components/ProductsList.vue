<template>
  <div>
       <ul v-for="p in products" v-bind:key="p">
            <ProductItem/>
            {{p}}
       </ul>
  </div>

</template>

<script>
import ProductItem from './ProductItem.vue'

export default {
  name: 'ProductsList',
    components: {
    ProductItem,
   
  },
   data(){
        return{
           products: []
        }
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