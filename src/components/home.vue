<template>
  <div class="home">
    <h1>Welcome to my Home Page</h1>
    <h3>This is a Website Talks About Video Games</h3>
    <img id = "game" src = "https://wallpaperaccess.com/full/774615.jpg">

  </div>

</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Welcome to my HomePage'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,h3{
  color: black;
  font-weight: bolder;
  background-color: whitesmoke;
  opacity: 0.7;
}

</style>
