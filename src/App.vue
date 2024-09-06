<template>
  <v-layout>
    <v-card class="mx-auto" color="grey-lighten-3" max-width="100%">
      <v-layout>
        <v-app-bar>
          <template v-slot:prepend>
            <v-app-bar-nav-icon></v-app-bar-nav-icon>
          </template>

          <v-app-bar-title>Appliance Repair</v-app-bar-title>

          <v-spacer></v-spacer>
          <nav class="d-flex justify-space-between ga-2">
            <router-link to="/">about</router-link>
            <router-link to="/Service">Service</router-link>
            <router-link to="/Order">How To Order</router-link>
            <router-link to="/Tesonials">Tesonials</router-link>
            <router-link to="/Faqs">Faqs</router-link>
            <router-link to="/Contact">Contact</router-link>
          </nav>
        </v-app-bar>

        <v-main>
          <v-container class="pa-0 bg-white" fluid>
            <intro-comp />
            <!------rating section-------->
            <rating-comp />
            <!---about section-->
            <about-comp />
            <!----------hero section----------->
            <hero-comp />
            <!------our services--------->
            <services-comp />
            <!----Order section----->
            <order-comp />
            <!--------- testimonial section  -->
            <testimonials-comp />
            <!--------- question section ------>
            <question-comp />
            <!-----------footer---------------->
            <footer-comp />
            <bottom-navigation />
          </v-container>
        </v-main>
      </v-layout>
    </v-card>
  </v-layout>
  <router-view />
</template>
<script>
import introComp from "./components/introComp.vue";
import ratingComp from "./components/ratingComp.vue";
import aboutComp from "./components/aboutComp.vue";
import heroComp from "./components/heroComp.vue";
import servicesComp from "./components/servicesComp.vue";
import orderComp from "./components/orderComp.vue";
import testimonialsComp from "./components/testimonialsComp.vue";
import questionComp from "./components/questionComp.vue";
import footerComp from "./components/footerComp.vue";
import bottomNavigation from "./components/bottomNavigation.vue";
export default {
  components: {
    introComp,
    ratingComp,
    aboutComp,
    heroComp,
    servicesComp,
    orderComp,
    testimonialsComp,
    questionComp,
    footerComp,
    bottomNavigation,
  },
};
</script>
<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap");
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  width: 604px;
  margin-right: 106px;
  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
