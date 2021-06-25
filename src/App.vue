<template>
  <div class="container">
    <div style="width: auto">
      <h1 class="primary row">Jérémy Appriou</h1>
    </div>
    <h2 class="secondary row">Développeur web</h2>
    <div class="row">
      <div class="flex f-row f-spa-eve w-100">
        <p class="btn-s btn-primary">smol btn</p>
        <p class="btn btn-primary">normal btn</p>
        <p class="btn-l btn-primary">big btn</p>
        <p class="btn-xl btn-primary">very big btn</p>
      </div>
    </div>
    <div class="row">
      <div class="flex f-row f-spa-eve w-100 f-wrap">
        <p class="btn btn-primary">btn primary</p>
        <p class="btn btn-secondary">btn secondary</p>
        <p class="btn btn-danger">btn danger</p>
        <p class="btn btn-light">btn light</p>
        <p class="btn btn-dark">btn dark</p>
        <p class="btn btn-background">btn background</p>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "App",
});
</script>

<style lang="scss">
@import "./assets/main.scss";

#app {
  display: flex;
  flex-direction: column;
}
</style>