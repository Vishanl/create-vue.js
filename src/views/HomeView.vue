<template>
  <h1>Главная</h1>
  <ProductCard/>
</template>

<script>

import items from "@/data/item"
import ProductCard from "@/components/ProductCard.vue"

export default {
  name: "HomeView",
  components: { 
    ProductCard
  },
  data(){
    return{
      items:items
    }
  }
}

</script>

