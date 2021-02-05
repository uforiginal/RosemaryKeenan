<template>
  <div id="app">
    <div class="header">
    <h1>Rosemary Keenan</h1>
    <h2><em>Junior Software Developer</em></h2>
    <div id="contact">
      <b-avatar class="header me" variant="info" size=10rem :src="require('./assets/me-professional-square.jpg')"></b-avatar>
      <b-avatar href="https://www.linkedin.com/in/rosemary-keenan-187a46202/" target="_blank" class="header me social" vairant="light"  size=4rem :src="require('./assets/linkedin1.png')" style="background-position: cover;"></b-avatar>
      <b-avatar href="https://twitter.com/omaha_rosemary" target="_blank" class="header me social" vairant="light"  size=4rem :src="require('./assets/twitter1.png')" style="background-position: cover;"></b-avatar>
      <b-avatar href="mailto: rosemary.lillian.keenan@gmail.com" class="header me social" vairant="light"  size=4rem :src="require('./assets/email1.png')" style="background-position: cover;"></b-avatar>
      <b-avatar href="https://github.com/uforiginal" target="_blank" class="header me social" vairant="light"  size=4rem :src="require('./assets/github1.png')" style="background-position: cover;"></b-avatar>
    </div>
    </div>
    <div id='content'>
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import Content from '@/components/Content.vue'
import Resume from '@/components/Resume.vue'
import pdf from 'vue-pdf'
export default {
  name: 'App',
  components: { Content, pdf, Resume }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Exo+2:wght@600&display=swap');

#app{
  position:relative;
  display:block;
  height: 100%;
  /*padding:1rem;*/
}

#app::before{
  content:"";
  background-image: url('./assets/LEDHex.jpg');
  background-size: cover;
  opacity:0.7;
  position:absolute;
  top:0;
  bottom:0;
  right:0;
  left:0;
  width:100%;
  height:50%;
  z-index:-3;
}

#app h1{
  text-align:left;
  font-size:7rem;
  font-family: 'Exo 2', sans-serif;
  color: whitesmoke;
  text-shadow: -2px 0 black, 0 2px black, 2px 0 black, 0 -2px black;
}

.header{
  padding: 2rem;
  display: block;
  text-align: left;
}

h1{
  width: 100%;
  margin-right: 80%;
  padding-top: 3%;
  /* text-shadow: 2px 2px 6px #fdfdfd;*/
  text-align: left;
  font-family: "Exo 2", sans-serif;
  font-size: 7rem;
}

#content{
  background-color: azure;
  border-top: 5px solid black;
  height: 100%;
  padding-bottom:0rem;
  margin-bottom: 0rem;
}

.text{
  margin: 5rem;
}

#intro{
  position: left;
  max-width: 50%;
  height: auto;
}

#contact{
  margin-top: 1rem;
}

.me{
  position: relative;
  padding: 0rem;
  top: 7rem;
  border: 5px solid black;
  display: inline-block;
}

.social{
  border: none;
  background-color: white;
}

footer{
  background-color: azure;
}
</style>
