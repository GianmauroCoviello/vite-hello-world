<!-- comprende la parte logica (javascript) -->
<script>
// importa la componente AppTitle.vue
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'; // importato altro componente che rappresenterà il jumbotron
export default {
  // oggetto che esporta la componente 
  components:{
    AppTitle,
    AppHero

  },
  
}
</script>
<!-- comprende la parte grafica (html) -->
<template>
  <div>
    <!-- riprende la componente figlio che sarà il file AppTitle.vue -->
    <AppTitle/>
    <AppHero/> <!--jumbotron-->
    
  </div>
</template>
<!-- comprende lo stile della pagina (css) -->
<style>
  
</style>