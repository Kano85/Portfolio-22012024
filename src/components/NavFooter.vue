<template>
  <div
    class="self-stretch bg-base-white overflow-hidden flex flex-row items-end justify-center pt-8 px-[17px] pb-[17px] text-center text-7xs-2 text-darkslateblue font-roboto"
  >
    <div
      class="flex-1 overflow-hidden flex flex-col items-center justify-start py-0 px-4 gap-[7px]"
    >
      <img
        class="w-[45.7px] h-[15.7px] relative overflow-hidden shrink-0"
        alt=""
        :src="logosWBSMedium"
      />
      <div class="w-[63px] h-1.5 relative inline-block">
        © 2022 WBS TRAINING AG
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "NavFooter",
    props: {
      logosWBSMedium: { type: String },
    },
  });
</script>
