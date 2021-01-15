<template>
  <v-app>
    <div class="home">
      <h1>Home Page</h1>
      <v-btn disabled class="pink white--text">click me</v-btn>
      <v-btn depressed class="pink">click me</v-btn>
      <v-btn flat class="pink">click me</v-btn>
      <v-btn depressed class="pink white--text">
        <v-icon left>mdi-email</v-icon>
        <span>Email Me</span>
      </v-btn>
      <v-btn depressed small class="pink white--text">
        <v-icon small left>mdi-email</v-icon>
        <span>Email Me</span>
      </v-btn>
      <v-btn depressed large class="pink white--text">
        <span>Email Me</span>
        <v-icon right large>mdi-email</v-icon>
      </v-btn>
      <v-btn depressed small dark color="purple">
        <span>Email Me</span>
        <v-icon right large>mdi-email</v-icon>
      </v-btn>
      <v-btn fab depressed small dark color="purple">
        <v-icon>mdi-cards-heart</v-icon>
      </v-btn>
    </div>
  </v-app>
</template>

<script>
export default {}
</script>
