<template>
  <div id="app">
    <TitleComponent></TitleComponent>
    <HeroComponent></HeroComponent>
  </div>
</template>

<script>
import TitleComponent from "./components/TitleComponent.vue";
import HeroComponent from "./components/HeroComponent.vue";


export default {
  name: 'App',
  components: {
    TitleComponent,
    HeroComponent
}
}
</script>

<style lang="scss">
* {
  margin : 0 ;
  padding: 0;
  box-sizing: border-box;
}

</style>
