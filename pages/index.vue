<template>
  <div>
    {{ cases }}
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import cases from '@/cases/cases.json'

export default Vue.extend({
  components: {},
  data() {
    return {
      cases
    }
  }
})
</script>

<style></style>
