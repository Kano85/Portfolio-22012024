<template>
  <section
    class="self-stretch bg-base-white overflow-hidden flex flex-col items-end justify-center py-2.5 px-10 box-border gap-[30px] max-w-full text-left text-31xl text-primary-main-1 font-roboto-mono mq700:gap-[15px]"
  >
    <h1
      class="m-0 h-[66px] relative text-inherit uppercase font-bold font-inherit inline-block max-w-full mq950:text-21xl mq450:text-11xl"
    >
      My recent work
    </h1>
    <div
      class="self-stretch flex flex-row flex-wrap items-center justify-start gap-[40px] max-w-full text-base mq700:gap-[20px]"
    >
      <GalleryCard
        frame5901="/frame-590-1@2x.png"
        trainspot="Trainspot"
        uIUX20232024="UIUX, 2023-2024"
        propMinWidth="367px"
        :onGalleryCardContainerClick="onGalleryCardContainerClick"
      /><GalleryCard
        frame5901="/frame-592-1@2x.png"
        trainspot="Kurskonfigurator"
        uIUX20232024="UI, Art drection"
        propMinWidth="378px"
        :onGalleryCardContainerClick="onGalleryCardContainer1Click"
      />
    </div>
  </section>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import GalleryCard from "./GalleryCard.vue";

  export default defineComponent({
    name: "MyRecentWork",
    components: { GalleryCard },
    methods: {
      onGalleryCardContainerClick() {
        this.$router.push("/");
      },
      onGalleryCardContainer1Click() {
        // Please sync "Page2-20012024" to the project
      },
    },
  });
</script>
