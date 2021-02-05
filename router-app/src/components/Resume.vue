<template>
    <div id="resume">
      <div class="text" id="intro">
        <h3><em>Hello!</em></h3>
        <p>I’m an ambitious software developer from Omaha, Nebraska. I graduated from the University of Nebraska at Omaha in December of 2020 and now I’m trying to find my next big project. If you’re looking for a dedicated developer, whether for your company, organization, or event, please take a look at my resume! I’d love to be a part of your vision, hope to hear from your soon!</p>
      </div>
      <div class="display">
        <pdf id="pdf" src='./static/test.pdf'/>
        <b-button variant="dark">Download Resume</b-button>
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
.display{
  width: 40%;
  margin-left: 20rem;
  margin-right: 20rem;
  text-align: center;
}

#pdf{
  border: solid black 5px;
}

button{
  margin: 1rem;
}
</style>
