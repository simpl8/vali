<template>
  <div>
    <Header></Header>
    <List></List>
    <Footer></Footer>
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  import List from './components/List.vue'
  import Footer from './components/Footer.vue'
  export default {
    name: "app",
    data() {
      return {}
    },
    components: {
      Header,
      List,
      Footer
    }
  }

</script>

<style scoped>

</style>
