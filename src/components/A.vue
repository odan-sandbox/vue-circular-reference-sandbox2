<template>
  <div>A <B /></div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import B from "./B.vue";

export default defineComponent({
  components: { B },
});
</script>
