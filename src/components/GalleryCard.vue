<template>
  <div
    class="flex-1 flex flex-col items-start justify-start gap-[10px] min-w-[367px] max-w-full cursor-pointer text-left text-base text-primary-main-1 font-roboto-mono"
    @click="onGalleryCardContainerClick"
    :style="galleryCardStyle"
  >
    <img
      class="self-stretch h-[450px] relative max-w-full overflow-hidden shrink-0 object-cover"
      loading="eager"
      alt=""
      :src="frame5901"
    />
    <div
      class="self-stretch flex flex-row flex-wrap items-center justify-between gap-[20px]"
    >
      <b class="relative">{{trainspot}}</b>
      <div class="relative">{{uIUX20232024}}</div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import type * as CSS from "csstype";

  export default defineComponent({
    name: "GalleryCard",
    props: {
      frame5901: { type: String },
      trainspot: { type: String },
      uIUX20232024: { type: String },
      propMinWidth: { type: [Object, Array, String, Number, Boolean] },
      onGalleryCardContainerClick: { type: Function },
    },
    computed: {
      galleryCardStyle(): CSS.Properties {
        return {
          minWidth: this.propMinWidth,
        };
      },
    },
  });
</script>
