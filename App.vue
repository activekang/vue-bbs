<template>
  <div id="app">
    <Header/>
    <BoardVisual/>
    <router-view/>
    <Footer/>
  </div>
</template>
<!-- �메인�이지 �정�2�-->
<!-- update 3 220527 -->
<!-- update 4 220527 0527 end-->

<script>
import Header from "@/components/Header";
import BoardVisual from "@/components/BoardVisual";
import Footer from "@/components/Footer";

export default {
  name: "App",
  components: {
    Header,
    BoardVisual,
    Footer
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
