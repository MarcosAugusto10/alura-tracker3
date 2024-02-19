//adicionar alguma interação com outros components e evento

<template>
  <footer class="footer">
    <div class="column is-pulled-right">
      <p>
        <strong>Teste de component footer</strong>
      </p>

    </div>
    <label class="texto">Texto label</label>
  </footer>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent(
  {
    name: "FooterComponent"
  })
</script>
<style>
.texto {
  font-size: 50px;
  float: left;
}
</style>
