<template>
  <div
    class="w-[122px] flex-1 flex flex-col items-end justify-start gap-[8px] text-left text-4xs-1 text-base-silver font-source-sans-pro"
    :style="frameDivStyle"
  >
    <div
      class="w-[118px] flex flex-row items-center justify-start gap-[8px] text-secondary-dark-grey-900"
      :style="frameDiv1Style"
    >
      <img
        class="h-[12.2px] w-[12.2px] relative overflow-hidden shrink-0"
        loading="eager"
        alt=""
        :src="wBSDASH"
      />
      <b
        class="h-[11px] flex-1 relative tracking-[0.08px] leading-[140%] inline-block"
        >Allgemein</b
      >
      <div
        class="h-[18.3px] w-0.5 relative rounded-[12.69px] bg-primary-main-1"
      />
    </div>
    <div
      class="self-stretch flex flex-row items-center justify-start py-0 pr-1 pl-[4.059319019317627px] gap-[8.12px]"
    >
      <img
        class="h-[13.2px] w-[13.2px] relative min-h-[13px]"
        loading="eager"
        alt=""
        :src="icon2"
      />
      <div
        class="h-[11px] flex-1 relative tracking-[0.08px] leading-[140%] inline-block"
      >
        Meine Seminare
      </div>
      <div
        class="h-[18.3px] w-0.5 relative rounded-[12.69px] bg-primary-main-1 hidden"
      />
      <div
        class="h-[11px] w-[10.6px] flex flex-row items-start justify-start text-center text-6xs-1 text-base-white font-roboto"
      >
        <div
          class="self-stretch flex-1 rounded-[5.07px] bg-success-main flex flex-row items-center justify-center py-0 px-[3.298196792602539px]"
        >
          <div
            class="self-stretch flex-1 relative tracking-[0.2px] leading-[10.15px] font-extrabold"
          >
            2
          </div>
        </div>
      </div>
    </div>
    <div class="self-stretch flex flex-row items-start justify-start py-0 px-1">
      <div class="flex-1 flex flex-row items-start justify-start gap-[8px]">
        <img
          class="h-[12.2px] w-[12.2px] relative min-h-[12px]"
          alt=""
          :src="wBSList24px"
        />
        <div
          class="h-[11px] flex-1 relative tracking-[0.08px] leading-[140%] inline-block"
        >
          Seminarprogramm
        </div>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import type * as CSS from "csstype";

  export default defineComponent({
    name: "Frame",
    props: {
      wBSDASH: { type: String },
      icon2: { type: String },
      wBSList24px: { type: String },
      propFlex: { type: String },
      propWidth: { type: [Object, Array, String, Number, Boolean] },
      propAlignSelf: { type: String },
    },
    computed: {
      frameDivStyle(): CSS.Properties {
        return {
          flex: this.propFlex,
        };
      },
      frameDiv1Style(): CSS.Properties {
        return {
          width: this.propWidth,
          alignSelf: this.propAlignSelf,
        };
      },
    },
  });
</script>
