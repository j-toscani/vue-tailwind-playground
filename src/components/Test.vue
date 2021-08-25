<template>
  <section>
    <h2>{{ headline }}</h2>
    <div>
      <input v-model="headline" type="text" />
      <p>Type smth into the input to change the headline!</p>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent, ref } from "vue";

export default defineComponent({
  setup() {
    const headline = ref("Hello mate!");
    return { headline };
  },
});
</script>

<style></style>
