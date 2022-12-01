<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';

  export default {
    
    data() {
        return {
            messaggio: "Hello Tomas Belfonte ",
            messaggio2: " --- by Vite ----"
        };
    },
    components: { AppTitle, AppHero }
};
</script>
  
<template>
  <h1 class="coltirth" >{{ messaggio }}</h1>
  <h1 class="coltirth">{{messaggio2}}</h1>
  <h1 class="colsecond">Ecco il mio primo file in Vite</h1>
  <h1 class="colfirst">Qui sotto il content creato da AppTitle.vue:</h1>
  <AppTitle></AppTitle>
  <h1 class="colfirst">Qui sotto il content creato dal Bonus AppHero.vue</h1>
  <AppHero></AppHero>
</template>

<style scoped>
  .colfirst {
    color: blue;
  }

  .colsecond {
    color: yellowgreen;
  }

  .coltirth {
    color: red;
  }
</style>
