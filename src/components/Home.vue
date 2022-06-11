<template>
  <div class="hello">

    <div class="menu">
        <div class = "menu-item">
          Resume
      </div>
        <div class = "menu-item">
          Photography
      </div>
      <div class = "menu-item">
          About
      </div>
    </div>

    <div class ="name">
      <div class="picture">
        <img src ="../assets/logogif.gif" class = "image">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home-page',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#app{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -mo-os-font-smoothing: black;
  color: white;

  padding:0;
  margin:0;
}

body{
  background: #080808;
  padding:0;
  margin:0;
}
.name{
  border: 1px solid black;
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: fit-content;
}

.picture{
  margin: 5 px;
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
}

.image{
  width:100%;
}

.menu{
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
  height: 60px;
}

.menu-item{
  flex: 1;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: space-around;
}

.menu-text{
  font-size: 20px;

}




</style>
