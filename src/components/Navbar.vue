<template>
    <div class="nav-container">
        <ul>
            <li><a>Home</a> </li>
            <li><a>About</a></li>
            <li><a>Contact</a></li>
        </ul>
    </div>
  
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
.nav-container{
    display: flex;
    flex-direction: row;
    justify-content: center;
      box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    padding: 20px
}


ul{
    display: flex;
    flex-direction: row;
}

li{
    list-style: none;
    margin: 0px 20px 0px;
    color: black;
    font-size: 25px;
}
</style>