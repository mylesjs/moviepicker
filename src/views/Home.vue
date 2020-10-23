<template>
  <div class="home">
       <h4 id="home"> Pick the genre movie you're in the mood to watch. </h4><br>

  <b-container>
    <b-row class="b-row" align-h="center" col="auto">
      <b-col><b-button @click="tester()" variant="info">Action</b-button></b-col>
      <b-col><b-button variant="info">Adventure</b-button></b-col>
      <b-col><b-button variant="info">Animation</b-button></b-col>
      <b-col><b-button class="btn btn-danger" variant="info">Comedy</b-button></b-col>
    </b-row><br>
    <b-row class="b-row" align-h="center">
      <b-col><b-button variant="info">Crime</b-button></b-col>
      <b-col><b-button variant="info">Drama</b-button></b-col>
      <b-col><b-button variant="info">Fantasy</b-button></b-col>
      <b-col><b-button variant="info">Historical</b-button></b-col>
    </b-row><br> 
    <b-row align-h="center">
      <b-col><b-button variant="info">Horror</b-button></b-col>
      <b-col><b-button variant="info">Magical Realism</b-button></b-col>
      <b-col><b-button variant="info">Mystery</b-button></b-col>
      <b-col><b-button variant="info">Paranoid Fiction</b-button></b-col>
    </b-row><br>
    <b-row align-h="center">
      <b-col><b-button variant="info">Philosophical</b-button></b-col>
      <b-col><b-button variant="info">Politcal</b-button></b-col>
      <b-col><b-button variant="info">Romance</b-button></b-col>
      <b-col><b-button variant="info">Saga</b-button></b-col>
    </b-row><br>
    <b-row align-h="center">
      <b-col><b-button variant="info">Satire</b-button></b-col>
      <b-col><b-button variant="info">Science Fiction</b-button></b-col>
      <b-col><b-button variant="info">Social</b-button></b-col>
      <b-col><b-button variant="info">Speculative</b-button></b-col>
    </b-row><br>
    <b-row align-h="center">
      <b-col><b-button variant="info">Thriller</b-button></b-col>
      <b-col><b-button variant="info">Urban</b-button></b-col>
      <b-col><b-button variant="info">Western</b-button></b-col>
      <b-col><b-button variant="info">Other</b-button></b-col>
    </b-row>
  </b-container>

  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  components: {

  },
  methods : {
    tester() {
      this.$router.push("movie");
    }
  }

}
</script>

<style>
#home {
  color: violet;
}

</style>

