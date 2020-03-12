<template>
  <div id="app">
    
    <ProductsList/>
    <ProductForm/>
    
  </div>
</template>

<script>
import ProductsList from './components/ProductsList.vue'
import ProductForm from './components/ProductForm.vue'

export default {
  name: 'App',
  components: {
    ProductsList,
    ProductForm
  }
}
</script>

<style>
#app {

}
</style>
