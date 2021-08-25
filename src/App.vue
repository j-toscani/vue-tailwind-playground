<template>
  <main>
    <h1>{{ message }}</h1>
    <section>
      <Test />
    </section>
  </main>
</template>

<script lang="ts">
import { defineComponent, ref } from "vue";
import Test from "@/components/Test.vue";

export default defineComponent({
  components: { Test },
  setup() {
    const message = ref("Hello!");
    return { message };
  },
});
</script>
