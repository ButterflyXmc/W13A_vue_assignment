<template>
<!-- Can only use #app, because vue only accepts app as an ID -->
  <div id="app">
    <!-- 3. USING the components -->
    <HeaderComponent/>
    <BodyComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
// 1. DECLARING the components
import HeaderComponent from '@/components/HeaderComponent.vue';
import BodyComponent from '@/components/BodyComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';

export default {
    name : 'App',
    // 2. REGISTERING the components
    components : {
      HeaderComponent,
      BodyComponent,
      FooterComponent,
    }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
