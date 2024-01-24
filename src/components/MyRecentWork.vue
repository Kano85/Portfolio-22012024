<template>
  <section
    class="self-stretch bg-white overflow-hidden flex flex-col items-end justify-center py-5 px-10 box-border gap-[20px] max-w-full shrink-0 text-left text-31xl text-primary-main-1 font-roboto-mono"
    data-scroll-to="myRecentWork"
  >
    <h1
      class="m-0 h-[66px] relative text-inherit uppercase font-bold font-inherit inline-block max-w-full mq450:text-11xl mq925:text-21xl"
    >
      My recent work
    </h1>
    <GroupOfHorizontalCards
      frame589="/frame-589@2x.png"
      frame5893="/frame-5893@2x.png"
      propHeight="450px"
      propHeight1="450px"
      :onGalleryCardContainerClick="onGalleryCardContainerClick"
      :onGalleryCardContainer1Click="onGalleryCardContainer1Click"
    /><GroupOfHorizontalCards
      frame589="/gallery-card@2x.png"
      frame5893="/frame-590@2x.png"
      propHeight="443.3px"
      propHeight1="443.3px"
    /><GroupOfHorizontalCards
      frame589="/frame-5892@2x.png"
      frame5893="/frame-5891@2x.png"
      propHeight="443.3px"
      propHeight1="443.3px"
    />
  </section>
</template>
<script>
  import { defineComponent } from "vue";
  import GroupOfHorizontalCards from "./GroupOfHorizontalCards.vue";

  export default defineComponent({
    name: "MyRecentWork",
    components: { GroupOfHorizontalCards },
    methods: {
      onGalleryCardContainerClick() {
        this.$router.push("/");
      },
      onGalleryCardContainer1Click() {
        this.$router.push("/page220012024");
      },
    },
  });
</script>
