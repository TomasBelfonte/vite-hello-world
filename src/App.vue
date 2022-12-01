<script>
  export default {
    data () {
      return {
        messaggio : "Hello Tomas Belfonte ",
        messaggio2 : " --- by Vite ----"
      };
    }
  };
</script>
  
<template>
  <h1>{{ messaggio }}</h1>
  <h1>{{messaggio2}}</h1>
  <h1 class="lead">Ecco il mio primo file in Vite</h1>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
