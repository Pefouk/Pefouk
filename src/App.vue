<template>
  <div id="header">
    <div class="animated animate fade-in instant" style="width: 100vw">
      <h1 class="header title primary animation slow pulseFromTop hover">
        Jérémy Appriou
      </h1>
    </div>
  </div>
  <div id="content">
    <div class="container">
      <div class="row animated">
        <h3 class="secondary animate fade-in first">Développeur web</h3>
        <p class="animate slideFromLeft second">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Obcaecati debitis culpa autem impedit reprehenderit ipsum quam id! Ducimus, eveniet quos? Quibusdam consectetur eveniet voluptate sit beatae aperiam velit alias labore!
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, unde adipisci voluptates repellat assumenda fuga reprehenderit, rem itaque tempora ex eos at ad laborum? Expedita, culpa perferendis! Unde, ea aut.
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Explicabo reprehenderit fugiat expedita eos unde beatae magni aut nihil, aspernatur, aliquam nisi non! Ad, ullam perferendis odit officia inventore maxime in.
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi accusantium aliquid eaque saepe corrupti voluptatem reprehenderit ex soluta, laboriosam ipsa cumque earum fugiat! Aperiam, explicabo odio fuga sint fugit facilis?
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Saepe non recusandae cum nam velit fugiat laboriosam obcaecati, omnis id officia distinctio temporibus maiores sunt ipsa neque quo error unde et!
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Amet ratione quas numquam consectetur error consequuntur iure impedit at debitis praesentium ducimus tenetur quo quae eum saepe iusto, aliquid vel ullam.
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corporis debitis repellendus corrupti? At id, cum quidem doloremque, quisquam quia vitae inventore eum quam eius, asperiores possimus sunt dolor rem dicta.
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt, et aliquam, quod ipsam corporis sint cum quaerat minima eius asperiores eligendi modi ullam non deleniti doloribus? Atque rem culpa perspiciatis.
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi eius pariatur in. Hic, dolores ipsum laborum neque labore earum fuga aliquam tempore voluptas ut, laudantium, aspernatur corporis facilis? Quibusdam, eligendi!
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti deserunt, sint architecto, excepturi officia nostrum vel rem dignissimos magni illum fugiat sed incidunt doloribus fuga modi quaerat temporibus corporis quas!
        </p>
        <h3 class="secondary animate slideFromRight third">Gros texte aléatoire</h3>
        <p class="animate slideFromLeft fourth">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deserunt, ipsum corrupti nemo sint eaque nobis iste consequatur magnam molestias illo libero ad nisi asperiores cupiditate! Soluta ratione pariatur consequuntur minima?</p>
      </div>
      <div class="row animate slideFromTop fourth">
        <a href="https://www.linkedin.com/in/j%C3%A9r%C3%A9my-appriou-772186159/">LinkedIn</a>
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