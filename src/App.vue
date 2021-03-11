<template>
  <div id="app">
    <NavBar></NavBar>
    <Header></Header>
    <Body></Body>
    <Footer></Footer>

    <router-view />
    <test></test>
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import Header from "./components/Header";
import Body from "./components/Body";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    NavBar,
    Header,
    Body,
    Footer,
  },
};
</script>

<style>
@import "./components/Header.css";
@import "./components/Body.css";
@import "./components/Footer.css";
@import url("https://fonts.googleapis.com/css2?family=Cabin&display=swap");
#app {
  font-family: "Cabin", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: black;
}
</style>
