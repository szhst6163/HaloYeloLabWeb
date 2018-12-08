<template>
  <div>
    <button @click="page1">sadasd</button>
  </div>
</template>
<style>
</style>
<script>
  export default {
    data() {
      return {
      }
    },
    components: {
    },
    mounted(){
    },
    methods: {
      page1(){
        this.$router.push({name:"page1"})
      },
      reset() {
      },
      handleSearchComplete(res) {
      }
    }
  }
</script>
