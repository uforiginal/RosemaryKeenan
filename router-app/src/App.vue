<template>
  <div id="app">
    <h1>Rosemary Keenan</h1>
    <div id='content'>
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import Content from '@/components/Content.vue'
export default {
  name: 'App',
  components: { Content }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: white;
  margin: 0 auto;
  background-image: url('./assets/LEDHex.jpg');
  background-size: cover;
}

#billboard{
  /*margin-bottom: 5%;*/
  width: 100%;
}

#content{
  margin-left:25%;
  width: 50%;
}

#head-img{
  max-width: 100%;
  height: auto;
}

h1{
  width: 100%;
  margin-right: 80%;
  padding-top: 3%;
  /* text-shadow: 2px 2px 6px #fdfdfd;*/
  text-align: left;
  font-family: "Exo-2", sans-serif;
  font-size: 7rem;
}
</style>
