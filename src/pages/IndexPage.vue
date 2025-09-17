<template>
  <q-img
    src="https://picsum.photos/1920/1080?grayscale"
    class="absolute-full"
  >

  <template v-slot:loading>
          <div
            class="text-subtitle1 text-red"
            style="position: fixed; top: 200px; left: 0; width: 100%; z-index: 1; text-align: center; "
          >
            <q-spinner
        color="primary"
        size="3em"
        :thickness="10"
      />
          </div>
        </template>

  </q-img>


  <q-page class="flex flex-center">

    <q-card class="q-pa-md text-center">
      <q-card-section>
        <div class="text-h4 text-bold text-blue">Pablo Montesano</div>
        <div class="text-subtitle1 text-italic">Consultoría y desarrollo web</div>

        <div class="text-overline text-italic">
        <a href="mailto:info@pablomontesano.com" class="text-blue pm-link">
            info@pablomontesano.com
          </a>
        </div>
      </q-card-section>

    </q-card>

  </q-page>
</template>

<script setup>
setInterval(() => {
  location.reload()
}, 50000)
</script>


<style scoped>
.pm-link {
  text-decoration: none;
  color: #1976d2;
  /* Color azul de Quasar */
}
</style>
