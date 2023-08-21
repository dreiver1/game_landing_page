<template>
  <q-layout view="hHh lpR fFf">

    <div class="text-white header" style="background-color: rgba(0, 0, 0, 0);">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar class="q-pr-md">
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
          Joginho de luta 2D
        </q-toolbar-title>
        <q-tabs v-model="tab" shrink stretch aria-checked="true">
          <q-route-tab to="/" label="Home" />
          <q-route-tab to="/" label="About US" />
          <q-route-tab to="/" label="Youtube" />
          <q-route-tab to="/" label="Contact ME" />
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

.page-content {
}
</style>
