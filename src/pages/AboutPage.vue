<template>
  <q-page class="column full-width items-center content-center justify-center" style="background-image: url('src/assets/bg.png'); background-size: cover;">
    <div class="row flex-center full-width col-12">
      <div class="flex flex-center col-7 text-white about ">
        <div class="text-h4 q-ma-lg">
        Quem somos nos?
        </div>
      <div class="flex flex-center text-h5">
        Somos uma equipe composta por estudantes de diversos periodos de engenharia de computação da unidade academica de belo jardim da universisdade federal de pernambuco.
         O game blind Fighters foi desenvolvido para a disciplina de projeto interdisciplinar 1!
      </div>
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

.about .text-h4 {
  font-weight: bolder;
  text-shadow: 1px 1px 2px black;
}

.about .text-h5 {
  font-weight: bolder;
  text-shadow: 1px 1px 2px black;
}

.text-h3 {
  font-size: xx-large;
  font-weight: bold;
  text-shadow: 3px solid black;
  padding: 25px;
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: rgba(14, 14, 14, 0.692);
}

.icon-img {
  width: fit-content;
  height: 24px;
}
</style>
