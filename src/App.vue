<template>
  <v-app>
    <Systembar/>
    <AppBar/>
    
    <v-main>
     <Navdraw/>
    </v-main>

    <Footer/>
    <Navbot/>
  </v-app>
</template>

<script>
import Footer from './components/Footer';
import Navbot from './components/Navbot';
import Systembar from './components/Systembar';
import AppBar from './components/Appbar';
import Navdraw from './components/Navdraw';



export default {
  name: 'App',

  components: {
    Footer,
    Navbot,
    Systembar,
    AppBar,
    Navdraw,
  },

  data: () => ({
    //
  }),
};
</script>
