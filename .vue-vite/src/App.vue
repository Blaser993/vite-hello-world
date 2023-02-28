<script>

import AppTitle from "./components/AppTitle.vue"


export default{

  components: {
    AppTitle
  },

  data (){
    return {
      message: "ciao vite",
    }
  },

  methods:{
    method(){
      console.log(method)
    }
  }
}
</script>

<template>


  <AppTitle></AppTitle>

  <div>
    <h1>{{message}}</h1>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>

  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
