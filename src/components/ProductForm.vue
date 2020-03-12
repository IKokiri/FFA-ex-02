<template>
  <div>
     <form @submit="onFormSubmit">
      <p>
        <label>Produto:</label>
        <input type="text">
      </p>
      <p>
        <label>Preço:</label>
        <input type="text">
      </p>
      <button type="submit">Enviar</button>
    </form>
  </div>

</template>

<script>
export default {
  name: 'ProductForm',
  props: {
    msg: String
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 p {
        width: 20%;
        display: inline-block;
       
    }
</style>