// JS
<script setup>
import { computed } from 'vue'
import { AppState } from './AppState.js'
import { ref } from "vue";

const cheese = ref(0)

</script>


// HTML
<template>
  <main>
    <div class="container">
      <section class="row">
        <div class="col-12">
          <div>
            <button @click="cheese++" class="btn btn-primary my-3">{{ cheese }} CHEESE</button>
          </div>
        </div>
      </section>
    </div>
  </main>
</template>


// styles
<style lang="scss">
@import "./assets/scss/main.scss";

</style>