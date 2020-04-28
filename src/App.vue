<template>
  <v-app>
    <Navbar/>

    
    <Content/>
    <!-- <HelloWorld/> -->
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import Navbar from './components/Navbar.vue'
import Content from './components/Content.vue'

export default {
  name: 'App',

  components: {
    // HelloWorld,
    Navbar,
    Content
},

  data: () => ({
    //
  }),
};
</script>
