<!-- comprende la parte logica (javascript) -->
<script>
// importa la componente AppTitle.vue
import AppTitle from './components/AppTitle.vue';
export default {
  // oggetto che esporta la componente 
  components:{
    AppTitle

  },
  
}
</script>
<!-- comprende la parte grafica (html) -->
<template>
  <div>
    <!-- riprende la componente figlio che sarà il file AppTitle.vue -->
    <AppTitle/>
    
  </div>
</template>
<!-- comprende lo stile della pagina (css) -->
<style>
  
</style>