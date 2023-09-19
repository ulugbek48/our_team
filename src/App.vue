<template>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Oswald:wght@200;300;400;500;600;700&family=Source+Serif+4:ital,opsz,wght@0,8..60,200;0,8..60,300;0,8..60,400;0,8..60,500;1,8..60,200;1,8..60,300;1,8..60,400;1,8..60,500&display=swap"
    rel="stylesheet"
  />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;1,100;1,200;1,300;1,400;1,500&display=swap"
    rel="stylesheet"
  />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Vollkorn:ital,wght@0,400;0,500;0,600;1,400;1,500;1,600&display=swap"
    rel="stylesheet"
  />
  <div class="wrapper">
    <Navbar/>
    <NavImg/>
    <Brands/>
    <Recent/>
    <Teams/>
    <Rectan/>
    <Touchs/>
    <Footer/>
  </div>
</template>


<script setup>
  import Navbar from "./components/navbar.vue"
  import NavImg from "./components/navimg.vue"
  import Brands from "./components/brandbox.vue"
  import Recent from "./components/recent.vue"
  import Teams  from "./components/team.vue"
  import Rectan from "./components/rectangle.vue"
  import Touchs from "./components/touch.vue"
  import Footer from "./components/footer.vue" 
</script>


<style lang="scss">
* {
  list-style: none;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  box-sizing: border-box;
  text-decoration: none;
  padding: 0;
  margin: 0;
  scroll-behavior: smooth;
}
.wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-left: auto;
  margin-right: auto;
}
</style>
