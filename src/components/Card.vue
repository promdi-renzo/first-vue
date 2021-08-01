<template>
  <div class="card-container">
      <img src="https://picsum.photos/200" alt="pic">
      <div class="content">
        <h3><b>Renzo Cabarios</b></h3>
        <p>Software Engineer</p>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Card'
}
</script>

<style scoped>
.card-container{
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 20%;
  margin: 20px
}
.card-container:hover{
      box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}
.content{
    padding: 19px 16px;
}

img{
      border-radius: 5px 5px 0 0;
      width: 100%
}
</style>