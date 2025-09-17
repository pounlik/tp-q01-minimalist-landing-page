<template>
  <q-layout view="hHh Lpr fFf"> <!-- Be sure to play with the Layout demo on docs -->

    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title>
          Pablo Montesano
        </q-toolbar-title>
        <div class="">{{ new Date().getFullYear() }}</div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="text-center" elevated>
      <div class="text-caption">
        Made with Quasar
        <q-icon name="favorite" color="red" size="14px" class="q-mx-xs" />
        by Pablo Montesano
      </div>
    </q-footer>

  </q-layout>
</template>

<script setup>

</script>
