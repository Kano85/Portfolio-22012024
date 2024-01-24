<template>
  <div
    class="self-stretch flex flex-row items-center justify-between py-0 px-2.5 box-border gap-[20px] max-w-full text-left text-base text-white font-roboto-mono mq975:flex-wrap"
    data-scroll-to="headerContainer"
  >
    <div
      class="w-[530px] flex flex-row items-center justify-start py-5 px-0 box-border gap-[24px] max-w-full mq450:flex-wrap"
    >
      <div
        class="w-[82px] flex flex-row items-start justify-start gap-[12px] cursor-pointer"
        @click="onWBSArrowInstanceClick"
      >
        <img
          class="h-6 w-6 relative object-contain min-h-[24px]"
          loading="eager"
          alt=""
          src="/wbs-arrow@2x.png"
        />
        <div class="flex-1 relative font-medium">Back</div>
      </div>
      <div class="flex flex-row items-start justify-end gap-[12px]">
        <div class="relative font-medium">Trainer:in Managment</div>
        <img
          class="h-6 w-6 relative min-h-[24px] cursor-pointer"
          loading="eager"
          alt=""
          src="/wbs-arrow-2.svg"
          @click="onWBSArrowIcon1Click"
        />
      </div>
    </div>
    <h1
      class="m-0 h-[66px] relative text-31xl uppercase font-bold font-inherit inline-block mq450:text-11xl mq975:text-21xl"
    >
      Trainspot
    </h1>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "NavigationBar",
    methods: {
      onWBSArrowInstanceClick() {
        this.$router.push("/portfolio20012024");
      },
      onWBSArrowIcon1Click() {
        this.$router.push("/");
      },
    },
  });
</script>
