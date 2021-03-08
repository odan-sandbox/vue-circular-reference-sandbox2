<template>
  <div>B: <A /></div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import BaseA from "./A.vue";

const A = BaseA as ReturnType<typeof defineComponent>;
export default defineComponent({
  components: { A },
});
</script>
