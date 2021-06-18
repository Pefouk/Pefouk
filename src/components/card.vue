<template>
  <div class="card">
    <div class="img">
      <img :src="img.src" :alt="img.alt">
    </div>
    <p class="title">{{title}}</p>
    <p class="small">{{text}}</p>
  </div>

</template>

<script>
export default {
  name: "card",
  props: ['title', 'img', 'text']
}
</script>

<style scoped>
.title {
  font-size: 20px;
}
.img {

}
.card {
  border-radius: 25px;
  border: solid 1px grey;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  flex-direction: column;
}
</style>
