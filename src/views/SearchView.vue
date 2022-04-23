<template>
  <div>
   
    <MealInfo/>
    <input type = "text">
    <button>Search</button>
  </div>
</template>

<script>
import MealInfo from '@/components/MealInfo.vue'
    export default {
  components: { MealInfo },
        name : "SearchView"
    }
</script>

<style lang="scss" scoped>

</style>