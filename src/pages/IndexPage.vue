<template>
  <q-page class="row full-width items-center wrap" style="background-image: url('https://images.alphacoders.com/128/1289055.jpg'); background-size: cover;">
    <div class="col-6 wrap text-h3 text-white padding">
        Unindo Forças Além da Visão: O Poder da Luta em um Mundo de Realidade Aumentada Inclusiva.
    </div>
    <div class="col-5" style="display: flex; align-items: center; justify-content: end;">
        <q-btn size="xl" color="red" text="white">Obter Game</q-btn>
    </div>
    <div class="row text-h6 col-12 text-white q-pa-sm" style="display: flex; align-items: center; justify-content: start;">
        <div class="col-1">
          Folow me:
        </div>
        <div class="q-pa-md">
          <q-btn round><img class="icon-img" src="../assets/instagram.png" alt="instagram"></q-btn>
        </div>
        <div class="q-pa-md">
          <q-btn round><img class="icon-img" src="../assets/youtube.png" alt="instagram"></q-btn>
        </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
<style>

.text-h3 {
  font-weight: bolder;
  text-shadow: 1px 1px 2px black;
  padding: 25px;
}

.icon-img {
  width: fit-content;
  height: 24px;
}
</style>
