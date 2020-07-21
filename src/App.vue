<template>
  <div id="app">
    <Header/>
    <BoardVisual/>
    <router-view/>
    
  </div>
</template>

<script>
import Header from "@/components/Header";
import BoardVisual from "@/components/BoardVisual";
export default {
  name: "App",
  components: {
    Header,
    BoardVisual
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