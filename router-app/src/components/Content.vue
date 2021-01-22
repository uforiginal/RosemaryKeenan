<template>
    <div id="app">
        <h1>Rosemary Keenan</h1>
        <b-card-group deck align="center">
        <b-card
          title="Work Expirience"
          tag="article"
          style="max-width: 20rem; background-color: #ffe6e6;"
          class="mb-3"
          >
          <b-card-text>View my past positions at various organizations</b-card-text>
          <b-button v-on:click="toggle(resume)" style="background-color: rosybrown;" ><b-icon icon="star-fill"></b-icon></b-button>
        </b-card>
        <b-card
          title="Community Work"
          tag="article"
          style="max-width: 20rem; background-color: #ffe6e6;"
          class="mb-3"
          >
          <b-card-text>See how I give back to my community</b-card-text>
          <b-button style="background-color: rosybrown;"><b-icon icon="star-fill"></b-icon></b-button>
        </b-card>
      </b-card-group>
      <b-card-group deck>
        <b-card
            title="Education"
            tag="article"
            style="max-width: 20rem; background-color: #ffe6e6;"
            class="mb-3"
            >
          <b-card-text>A brief history of my educational background</b-card-text>
          <b-button style="background-color: rosybrown;"><b-icon icon="star-fill"></b-icon></b-button>
        </b-card>
        <b-card
            title="Acknowledgements"
            tag="article"
            style="max-width: 20rem; background-color: #ffe6e6;"
            class="mb-3"
            >
          <b-card-text>Click here to view some of the generous awards and acknowledgements I've recieved</b-card-text>
          <b-button style="background-color: rosybrown;"><b-icon icon="star-fill"></b-icon></b-button>
        </b-card>
      </b-card-group>
    </div>
</template>

<script>
// import HelloWorld from '../components/HelloWorld.vue'
// import About from '../components/About.vue'
// import Resume from '../components/Resume.vue'

export default {
  name: 'Content'

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
  background-image: url("../assets/BeBrilliantNeon.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: 80% 100%;
}

b-card-group {
  margin: 0 auto;
}
</style>
