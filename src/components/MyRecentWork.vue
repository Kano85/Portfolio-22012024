<template>
  <section
    class="self-stretch bg-white overflow-hidden flex flex-col items-end justify-center py-[1.25rem] px-[2.5rem] box-border gap-[1.25rem] max-w-full shrink-0 text-left text-[3.13rem] text-primary-main-1 font-roboto-mono"
    data-scroll-to="myRecentWork"
  >
    <h1
      class="m-0 h-[4.13rem] relative text-inherit uppercase font-bold font-inherit inline-block max-w-full mq925:text-[2.5rem] mq450:text-[1.88rem]"
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
      propHeight="27.71rem"
      propHeight1="27.71rem"
    /><GroupOfHorizontalCards
      frame589="/frame-5892@2x.png"
      frame5893="/frame-5891@2x.png"
      propHeight="27.71rem"
      propHeight1="27.71rem"
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
        this.$router.push("/page120012024");
      },
      onGalleryCardContainer1Click() {
        this.$router.push("/");
      },
    },
  });
</script>
