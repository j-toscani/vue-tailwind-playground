<template>
  <header>
    <div class="header-inner">
      <h1>Hello!</h1>
      <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/about"> About </router-link>
        <router-link to="/profile"> Profile </router-link>
      </nav>
    </div>
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Header",
});
</script>

<style lang="postcss">
header {
  @apply bg-gray-300;
}

.header-inner {
  @apply container mx-auto flex flex-row align-middle justify-between;
  @apply py-8;
  @apply text-2xl;
}

nav {
  @apply flex gap-5;
}
</style>
