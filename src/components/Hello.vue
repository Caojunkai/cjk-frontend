<template>
    <div id="hello">
        <h1>Shopping Cart Example</h1>
        <hr>
        <h2>Products</h2>
        <product-list></product-list>
        <hr>
        <cart></cart>
    </div>
</template>

<script>
  import ProductList from './ProductList.vue'
  import Cart from './Cart.vue'

  export default {
    name : 'hello',
    components: { ProductList, Cart }
  }
</script>
