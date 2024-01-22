<template>
  <div
    class="self-stretch flex flex-row items-center justify-between gap-[20px] max-w-full text-left text-base text-base-white font-roboto-mono mq1025:flex-wrap"
  >
    <div
      class="w-[530px] flex flex-row items-center justify-start py-5 px-0 box-border gap-[24px] max-w-full mq750:flex-wrap"
    >
      <div
        class="w-[82px] flex flex-row items-start justify-start gap-[12px] cursor-pointer"
        @click="onLineContainerClick"
      >
        <img
          class="h-6 w-6 relative object-contain min-h-[24px]"
          loading="eager"
          alt=""
          src="/wbs-arrow@2x.png"
        />
        <h1 class="m-0 flex-1 relative text-inherit font-medium font-inherit">
          Back
        </h1>
      </div>
      <div class="flex flex-row items-start justify-end gap-[12px]">
        <img
          class="h-6 w-6 relative min-h-[24px] cursor-pointer"
          loading="eager"
          alt=""
          src="/wbs-arrow-1.svg"
          @click="onWBSArrowIcon1Click"
        />
        <h1 class="m-0 relative text-inherit font-medium font-inherit">
          Trainspot
        </h1>
      </div>
      <div class="flex flex-row items-start justify-end gap-[12px]">
        <h1 class="m-0 relative text-inherit font-medium font-inherit">
          Trainer:in Managment
        </h1>
        <img
          class="h-6 w-6 relative min-h-[24px] cursor-pointer"
          loading="eager"
          alt=""
          src="/wbs-arrow-2.svg"
          @click="onWBSArrowIcon2Click"
        />
      </div>
    </div>
    <h1
      class="m-0 h-[66px] relative text-31xl uppercase font-bold font-inherit inline-block mq450:text-11xl mq1025:text-21xl"
    >
      Trainspot
    </h1>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "NavigationBar",
    methods: {
      onLineContainerClick() {
        this.$router.push("/portfolio20012024");
      },
      onWBSArrowIcon1Click() {
        this.$router.push("/portfolio20012024");
      },
      onWBSArrowIcon2Click() {
        // Please sync "Page2-20012024" to the project
      },
    },
  });
</script>
