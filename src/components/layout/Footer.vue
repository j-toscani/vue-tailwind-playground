<template>
  <footer>
    <img src="/imgs/logo.svg" alt="" />
    <address>
      <ul>
        <li>
          <span>Email: </span>
          <a href="mailto:me@you.com"> me@you.com </a>
        </li>
        <li>
          <span> Owner: </span>
          <span> Carl Heinz </span>
        </li>
        <li>
          <span>Tel:</span>
          <a href="tel:+555 445566"> +555 445566 </a>
        </li>
      </ul>
    </address>
  </footer>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Footer",
});
</script>

<style></style>
