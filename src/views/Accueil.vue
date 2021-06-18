<template>
  <h1>Hello world</h1>
  <Card :img="img" text="ouais" title="yes">
  </Card>
</template>

<script>
import Card from "@/components/card";

export default {
  name: "Accueil",
  components: {Card},
  data() {
    return {
      img: {
        src: "https://via.placeholder.com/350x150",
        alt: "placeholder pas ouf"
      },

    }
  }
}
</script>

<style scoped lang="sass">

</style>
