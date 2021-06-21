<template>
<h1>Jérémy Appriou</h1>
<h2>Développeur web et web mobile</h2>
<div>
  <p class="primary">Primaire</p><p class="secondary">Secondaire</p><p class="text">Text normal</p><p class="danger">Danger</p>
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'App',
})
</script>

<style lang="scss">
@import './assets/main.scss';
@import './assets/styles/colors.scss';

#app {
  display: flex;
  flex-direction: column;
}

</style>