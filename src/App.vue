<script>

// Qui importiamo i componenti che verranno usati
// import [NOME] from [PATH]
import headerBar from './components/headerBar.vue';
import mainContent from './components/mainContent.vue';
import footerContent from './components/footerContent.vue';



// Qui definiamo l'oggetto che conterrà la lista dei componenti importati, che verranno usati
export default{
  components: {
    headerBar,
    mainContent,
    footerContent
  }
}

</script>

<template>

  <header>
    <!-- Qui ho usato il componente HeaderBar -->
    <headerBar />
  </header>

  <main>
    <!-- Qui ho usato il componente mainComponent -->
    <mainContent />
  </main>

  <footer>
    <!-- Qui ho usato il componente mainComponent -->
    <footerContent />
  </footer>

</template>

<style scoped>



</style>
