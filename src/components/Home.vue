<template>
  <div class="hello">
    <div class="menu">
      <div class="menu-left">
        <div class="menu-item">
          Intro
        </div>
      </div>
      <div class="menu-l-center">
        <div class="menu-item">
          About
        </div>
      </div>
      <div class="menu-center-r">
        <div class="menu-item">
          Capabilities
        </div>
      </div>
      <div class="menu-right">
        <div class="menu-item">
            Projects
        </div>
      </div>
    </div>
    <div class="name-bg">
      <div class="img-bg">
        <img src="@/assets/img/1.png" class="letter-img">
      </div>
      <div class="img-bg">
        <img src="@/assets/img/3.png" class="letter-img"> 
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.name-bg{
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: center;
  width: 100vw;
  height: 100vh;
}
.img-bg {
  margin: 50px;
}

.letter-img{
  width: 100%;
}
.menu{
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  
}
.menu-item{
  flex: 1;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: bold;
  color: whitesmoke;
  text-transform: uppercase;
  letter-spacing: 3px;
  position: fixed;
}
.menu-item:hover{
  color: #D4F1F1;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
