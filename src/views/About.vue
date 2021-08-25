<template>
  <main>
    <h2>About</h2>
    <article>
      <div class="p-wrapper">
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ex tenetur
          qui eaque velit aliquam consequuntur necessitatibus quasi amet soluta
          doloremque. Totam provident aperiam nemo assumenda eos facere adipisci
          animi numquam!
        </p>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ex tenetur
          qui eaque velit aliquam consequuntur necessitatibus quasi amet soluta
          doloremque. Totam provident aperiam nemo assumenda eos facere adipisci
          animi numquam! Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Voluptatem, libero consequatur! Nobis nesciunt accusantium iure
          labore eius molestiae repellat a officia voluptate quae reprehenderit
          earum dolorem, fugit autem, itaque dolor.
        </p>
        <p>Lorem ipsum, dolor sit amet.</p>
      </div>
      <img src="https://picsum.photos/600/900" alt="" />
    </article>
  </main>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "About",
});
</script>

<style lang="postcss">
article {
  @apply flex flex-row align-middle flex-wrap;
}

.p-wrapper {
  @apply md:w-2/3;
}
p {
  @apply my-4;
}

img {
  @apply md:w-1/3;
}
</style>
