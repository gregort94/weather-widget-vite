<template>
  <VueMultiselect :show-labels="false">
  </VueMultiselect>
</template>

<script lang="ts" setup>
import VueMultiselect from 'vue-multiselect'
</script>

<style src="vue-multiselect/dist/vue-multiselect.css"></style>
<style>
.multiselect__option {
  color: var(--v-theme-on-background);
}

.multiselect__option--highlight {
  background: rgba(var(--v-theme-on-background), 0.1);
}

.multiselect__spinner::before, .multiselect__spinner::after {
  border-color: rgba(var(--v-theme-on-background), 0.6) transparent transparent;
}
</style>
