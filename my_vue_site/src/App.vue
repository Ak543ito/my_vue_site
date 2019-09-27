<template>
  <v-app id="inspire" >
      <Header/>
      <v-content>        
              <LandingPage />                 
      </v-content>
      <Footer/>
  </v-app>
</template>

<script>
import Under_Construction from './components/Under_Construction';
import Header from './components/Header/Header.vue';
import Footer from './components/Footer/Footer.vue';
import LandingPage from './views/LandingPage/LandingPage.vue'

export default {
  name: 'App',
  components: {
    Under_Construction,
    Header,
    Footer,
    LandingPage,
  },
  data: () => ({
    //
  }),
};
</script>
