<template>
    <div id="app position-absolute">
      <!-- Call Components -->
        <Header :data="dataHeader"/>
        <Jumbotron/>
        <Main/>
        <CallInAction/>
        <Footer/>
        <!-- Arrow that if click go to the header -->
        <a href="#" class="arrow-up-rf"> </a>
        
    </div>
</template>

<script>

// import data nav bar

import {navBarData} from "@/assets/scriptFiles/headerData"

// import components
import Header from "./components/Header.vue"
import Jumbotron from './components/Jumbotron.vue'
import Main from "./components/Main.vue"
import CallInAction from "./components/CallInAction.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',

  data(){
      return {
          // data of the nav bar
          dataHeader: navBarData,
    }
  },

  // Set MacroStructure of the WebSite
  components: {
    Header,
    Jumbotron,
    Main,
    CallInAction,
    Footer,
  },

  mounted(){
    // console.log(this.dataHeader);
  }

}
</script>

<style lang="scss">

// import bootstrap
@import "~bootstrap/scss/bootstrap";

@import "./src/assets/toolsStyle.scss";

// import general Settings
@import "./src/assets/generalStyle.scss";


</style>
