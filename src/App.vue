<template>
  <div>
    <app-menu tittle = "Megadron"></app-menu>
    <router-view />
    <appFooter />
  </div>
</template>

<script>
  import AppMenu from "@/components/AppMenu.vue";
  import AppFooter from "@/components/AppFooter.vue";
  export default {
    name: 'App',
    data(){
      return {
        
      }
    },
    methods: {
      
    },
    computed: {
      
    },
    mounted() {
      
    },
    components: {
      AppMenu,
      AppFooter
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
