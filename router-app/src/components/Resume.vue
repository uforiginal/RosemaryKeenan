<template>
    <div id="resume">
        <h3>Resume</h3>
        <div>
          <pdf src='./static/test.pdf'/>
          <router-link to="/"><b-button style="background-color: rosybrown;" ><b-icon icon="star-fill"></b-icon></b-button></router-link>
        </div>
    </div>
</template>
<script>
import pdf from 'vue-pdf'

export default {
  name: 'Resume',
  components: {
    pdf
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#resume{
  margin: 0 auto;
}
#billboard{
  /*margin-bottom: 5%;*/
  width: 100%;
  background-position: center;
  background-repeat: no-repeat;
  /*background-size: 80% 100%;*/
}
</style>
