<template>
  <q-page class="column full-width items-center content-center justify-center" style="background-image: url('https://images.alphacoders.com/128/1289055.jpg'); background-size: cover;">
    <div class="row justify-start full-width col-12">
      <div class="row flex-center wrap col-12 text-white about">
        <div class="text-h4 q-ma-lg col-8">
          Contatos:
        </div>
        <div class="text-h4 q-ma-lg col-8">
          <q-icon name="mail" class="text-black"></q-icon>
            email: blindfighters@gmail.com
        </div>
        <div class="text-h4 q-ma-lg col-8">
          <q-icon><img src="../assets/youtube.png"></q-icon>
          youtube: blindfighters
        </div>
        <div class="text-h4 q-ma-lg col-8">
          <a href="https://www.instagram.com/blindfightersofficial/" target="_blank" rel="noopener noreferrer">
            <q-icon><img src="../assets/instagram.png"></q-icon>
            Instagram: blindfightersofficial
          </a>
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

a {
  color: white;
  text-decoration: none;
}
</style>
