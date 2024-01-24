<template>
  <div
    class="self-stretch flex flex-row flex-wrap items-center justify-start gap-[40px] max-w-full text-left text-base text-primary-main-1 font-roboto-mono mq700:gap-[20px]"
  >
    <div
      class="flex-1 flex flex-col items-start justify-start gap-[10px] min-w-[367px] max-w-full cursor-pointer"
      @click="onGalleryCardContainerClick"
    >
      <img
        class="self-stretch h-[450px] relative max-w-full overflow-hidden shrink-0 object-cover"
        loading="eager"
        alt=""
        :src="frame589"
        :style="frameIconStyle"
      />
      <div
        class="self-stretch flex flex-row flex-wrap items-center justify-between gap-[20px]"
      >
        <b class="relative">Trainspot</b>
        <div class="relative">UIUX, 2023-2024</div>
      </div>
    </div>
    <div
      class="flex-1 flex flex-col items-start justify-start gap-[10px] min-w-[378px] max-w-full cursor-pointer"
      @click="onGalleryCardContainer1Click"
    >
      <img
        class="self-stretch h-[450px] relative max-w-full overflow-hidden shrink-0 object-cover"
        alt=""
        :src="frame5893"
        :style="frame5893IconStyle"
      />
      <div
        class="self-stretch flex flex-row flex-wrap items-center justify-between gap-[20px]"
      >
        <b class="relative">Kurskonfigurator</b>
        <div class="relative">UI, Art drection</div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "GroupOfHorizontalCards",
    props: {
      frame589: { type: String },
      frame5893: { type: String },
      propHeight: { type: [Object, Array, String, Number, Boolean] },
      propHeight1: { type: [Object, Array, String, Number, Boolean] },
      onGalleryCardContainerClick: { type: Function },
      onGalleryCardContainer1Click: { type: Function },
    },
    computed: {
      frameIconStyle() {
        return {
          height: this.propHeight,
        };
      },
      frame5893IconStyle() {
        return {
          height: this.propHeight1,
        };
      },
    },
  });
</script>
