<template>
    <div id="app">

      <!-- Call Components -->
        <Header/>
        <Jumbotron/>
        <Main/>
        <CallInAction/>
        <Footer/>

    </div>
</template>

<script>

// import components
import Header from "./components/Header.vue"
import Jumbotron from './components/Jumbotron.vue'
import Main from "./components/Main.vue"
import CallInAction from "./components/CallInAction.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',

  // Set MacroStructure of the WebSite
  components: {
    Header,
    Jumbotron,
    Main,
    CallInAction,
    Footer,
  }
}
</script>

<style lang="scss">

// import bootstrap
@import "~bootstrap/scss/bootstrap";

// import general Settings
@import "./src/assets/generalStyle.scss";


</style>
