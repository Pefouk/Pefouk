<template>
  <h1>Hello world</h1>
  <div class="card-deck">
    <Card :img="img" text="ouais" title="yes" date="20 decembre 1997" class="center"/>
    <Card :img="img" text="ouais" title="yes" date="20 decembre 1997" class="center"/>
    <Card :img="img" text="ouais" title="yes" date="20 decembre 1997" class="center"/>
    <Card :img="img" text="ouais" title="yes" date="20 decembre 1997" class="center"/>
  </div>
</template>

<script>
import Card from "@/components/card";

export default {
  name: "Accueil",
  components: {Card},
  data() {
    return {
      img: {
        src: "https://via.placeholder.com/1920x1080",
        alt: "placeholder pas ouf"
      },

    }
  }
}
</script>

<style scoped lang="sass">
@import "../assets/style.scss"
.card-deck
  display: flex
  justify-content: center
  flex-wrap: wrap
</style>
