<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <table>
      <tr>
        <td>
          <b-card
          title="Work Expirience"
          tag="article"
          style="max-width: 20rem;"
          class="mb-2"
          >
          <b-card-text>View my past positions</b-card-text>
          <b-button href="#" variant="primary"></b-button>
          </b-card>
        </td>
        <td>
          <b-card
          title="Community Work"
          tag="article"
          style="max-width: 20rem;"
          class="mb-2"
          >
          <b-card-text>See how I give back to my community</b-card-text>
          <b-button href="#" variant="primary"></b-button>
          </b-card>
        </td>
        <td>
          <b-card
            title="About Me"
            tag="article"
            style="max-width: 20rem;"
            class="mb-2"
            >
          <b-card-text>A brief history of Rosemary Keenan</b-card-text>
          <b-button href="#" variant="primary"></b-button>
          </b-card>
        </td>
      </tr>
    </table>
    
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
//import About from './components/About.vue'
//import Resume from './components/Resume.vue'

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
table{
  position: center;
  margin-left: auto;
  margin-right: auto;
}
</style>
