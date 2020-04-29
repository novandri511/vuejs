<template>
  <v-app>
    <Navbar/>

    
    <Content/>
    <!-- <HelloWorld/> -->
    <v-footer>
      <Footer/>
    </v-footer>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import Navbar from './components/Navbar.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',

  components: {
    // HelloWorld,
    Navbar,
    Content,
    Footer
},

  data: () => ({
    //
  }),
};
</script>
