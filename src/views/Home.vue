<template>
  <div class="home">
    <v-container>
      <HomePageImage></HomePageImage>
      <IndividualLessons></IndividualLessons>
      <br><br><br><br><br>
      <FAQ></FAQ>
    </v-container>
    <v-bottom-sheet>
    </v-bottom-sheet>
  </div>
</template>

<script>
// @ is an alias to /src

import IndividualLessons from "../components/IndividualLessons";
import HomePageImage from "../components/HomePageImage";
import FAQ from "../components/FAQ";

export default {
  name: 'home',
  components: {
      IndividualLessons,
      HomePageImage,
      FAQ
  }
}
</script>
