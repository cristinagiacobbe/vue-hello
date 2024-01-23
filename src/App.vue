<script>
export default {
  data() {
    return {
      message: "Questo è il risultato della faticosa impresa di stampare in pagina un messaggio usando Vuejs",
      image: "/emoticon.jpg"
    }

  }
}
</script>

<template>
  <h1>{{ message }}</h1>
  <img :src="image" alt="immagine non disponibile">
</template>

<style></style>
