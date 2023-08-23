<template>
  <q-layout view="hHh lpR fFf">

    <div class="text-white header" style="background-color: rgba(0, 0, 0, 0);">
      <q-toolbar>
        <q-toolbar-title class="row items-center">
          <q-avatar class="q-pr-xl">
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
            <!-- <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg"> -->
          </q-avatar>
         <div class="title">
          BLIND FIGHTERS
         </div>
        </q-toolbar-title>
        <q-tabs v-model="tab" shrink stretch aria-checked="true">
          <q-route-tab name="home" to="/" label="Home" />
          <q-route-tab name="about" to="/about" label="About US" />
          <q-route-tab name="youtube" to="/youtube" label="Youtube" />
          <q-route-tab name="conctact" to="/contact" label="Contact ME" />
        </q-tabs>
      </q-toolbar>
    </div>

    <q-page-container class="page-content">
      <router-view />
    </q-page-container>

  </q-layout>
</template>
<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      tab: ref('')
    }
  }
}
</script>

<style scoped>
.title {
  font-size: xx-large;
  font-weight: bolder;
  text-shadow: 1px 1px 2px black;
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: rgba(14, 14, 14, 0.692);
}

.q-tab.q-tab--active {
  background-color: #f44336;
  color: #fff;
}

.q-tab.q-tab{
  font-size: 20px;
  color: #fff;
}
.header {
  position: fixed;
  width: 100%;
  z-index: 1000;
  padding-top: 1%;
}

</style>
