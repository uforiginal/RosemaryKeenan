<template>
  <div id="app">
    <div id="billboard">
      <img src="./assets/me-professional.jpg" id="avatar"/>
    </div>
    <Content id="content"/>
  </div>
</template>

<script>
import Content from './components/Content.vue'

export default {
  name: 'App',
  components: {Content}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: bisque;
}

#billboard{
  margin-bottom: 5%;
  width: 100%;
  background-image: url("./assets/BeBrilliantNeon.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: 80% 100%;
}

#content{
  margin-left:25%;
  width: 50%;
}

#avatar{
  border-radius: 80%;
  border-style: double;
  width: 200px;
  height: auto;
  object-fit: cover;
  margin-right: 80%;
  margin-top: 10%;
}

b-card-group {
  margin: 0 auto;
}
</style>
