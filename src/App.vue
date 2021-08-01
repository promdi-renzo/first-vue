<template>
  <Navbar />
  <div class="content-container">
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
  </div>

  
</template>

<script>
import Navbar from './components/Navbar.vue'
import Card from './components/Card.vue'
export default {

  name: 'App',
  components:{
    Navbar,
    Card
  }
}
</script>

<style scoped>
*{
  margin: 0px;
  padding: 0px;
}

.content-container{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
</style>
