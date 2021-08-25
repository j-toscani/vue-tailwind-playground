<template>
  <header>
    <h1>Hello!</h1>
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about"> About </router-link>
      <router-link to="/profile"> Profile </router-link>
    </nav>
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Header",
});
</script>

<style></style>
