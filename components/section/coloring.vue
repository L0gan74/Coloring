<script setup lang="ts">

import ColoringItem from "~/components/item/coloring-item.vue";

defineProps<{
  coloringTitle: string
}>()

</script>

<template>
  <section class="coloring section-purple">
    <div class="section-container">
      <h2 class="section-title">
        {{ coloringTitle }}
      </h2>
     <ColoringItem/>
    </div>
  </section>
</template>

<style lang="scss">

</style>