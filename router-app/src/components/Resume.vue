<template>
    <div id="resume">
        <h3>Resume</h3>
        <div>
          <embed src="../assets/test.pdf" width="100%" height="600px" />
          <router-link to="/"><b-button style="background-color: rosybrown;" ><b-icon icon="star-fill"></b-icon></b-button></router-link>
        </div>
    </div>
</template>
<script>
export default {
  name: 'Resume'
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
</style>
