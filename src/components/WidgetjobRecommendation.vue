<template>
  <div
    class="h-[163px] w-[205px] flex flex-row items-center justify-center relative min-w-[205.4px] text-left text-5xs-2 text-primary-main-2 font-source-sans-pro mq450:flex-1"
  >
    <div
      class="h-full w-full absolute my-0 mx-[!important] top-[-0.5px] right-[0.1px] bottom-[0.5px] left-[-0.1px] rounded-[9.01px] bg-base-white overflow-hidden"
    />
    <div
      class="self-stretch flex-1 flex flex-col items-center justify-start py-0 px-[7.208159923553467px] gap-[3.6px] z-[1]"
    >
      <div
        class="self-stretch flex flex-col items-center justify-center pt-[7.208159923553467px] px-0 pb-[3.6040799617767334px] text-center text-4xs-1 text-secondary-dark-grey-900"
      >
        <div
          class="flex flex-row items-center justify-center py-0 px-5 gap-[7.21px]"
        >
          <img
            class="h-[10.8px] w-[10.8px] relative"
            loading="eager"
            alt=""
            :src="wBSArrow"
          />
          <div class="flex flex-col items-center justify-center">
            <b class="relative leading-[12.16px]">{{title}}</b>
            <div class="relative text-6xs-3 leading-[9.46px] text-base-gray">
              WBS Training • Remote • Vollzeit
            </div>
          </div>
          <img
            class="h-[10.8px] w-[10.8px] relative"
            loading="eager"
            alt=""
            :src="wBSArrow1"
          />
        </div>
      </div>
      <div
        class="self-stretch flex flex-col items-center justify-start gap-[3.6px]"
      >
        <b class="self-stretch relative leading-[10.81px]">Übersicht</b>
        <div
          class="self-stretch relative text-6xs-3 leading-[9.46px] text-secondary-dark-grey-900"
        >
          Egestas fringilla erat varius aliquam congue fames. Sapien vitae ut at
          amet pulvinar sed eu sed. Posuere a erat in hendrerit gravida. Diam
          fringilla tortor sit sapien semper neque eu. Cursus sit ut adipiscing
          massa massa pharetra.
        </div>
      </div>
      <div class="self-stretch flex flex-row items-start justify-center">
        <b class="flex-1 relative leading-[10.81px]">Skills</b>
      </div>
      <div
        class="self-stretch flex flex-row items-start justify-start gap-[3.6px] text-6xs-3 text-base-white"
      >
        <div
          class="rounded-11xs-8 bg-primary-main-2 flex flex-row items-start justify-start py-0 px-[0.9010199904441833px] whitespace-nowrap"
        >
          <div class="relative leading-[9.46px]">{{badgeText}}</div>
          <img
            class="h-[7.2px] w-[7.2px] relative hidden"
            alt=""
            :src="wBSCloseCancelDelete16px"
          />
        </div>
        <div
          class="rounded-11xs-8 bg-primary-main-2 flex flex-row items-start justify-start py-0 pr-px pl-[0.9010199904441833px]"
        >
          <div class="relative leading-[9.46px]">{{badgeText1}}</div>
          <img
            class="h-[7.2px] w-[7.2px] relative hidden"
            alt=""
            :src="wBSCloseCancelDelete16px1"
          />
        </div>
        <div
          class="rounded-11xs-8 bg-primary-main-2 flex flex-row items-start justify-start py-0 pr-px pl-[0.9010199904441833px]"
        >
          <div class="relative leading-[9.46px]">{{badgeText2}}</div>
          <img
            class="h-[7.2px] w-[7.2px] relative hidden"
            alt=""
            :src="wBSCloseCancelDelete16px2"
          />
        </div>
      </div>
      <div
        class="self-stretch h-[40.4px] flex flex-col items-center justify-end pt-[3.6040799617767334px] px-0 pb-[7.208159923553467px] box-border text-center text-6xs-3 text-base-white"
      >
        <div
          class="self-stretch rounded-11xs-8 bg-primary-main-1 overflow-hidden flex flex-row items-center justify-center py-[4.505099773406982px] px-[10.812239646911621px] whitespace-nowrap"
        >
          <div class="relative leading-[9.01px] font-semibold">
            {{buttonText}}
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "WidgetjobRecommendation",
    props: {
      wBSArrow: { type: String },
      title: { type: String },
      wBSArrow1: { type: String },
      badgeText: { type: String },
      wBSCloseCancelDelete16px: { type: String },
      badgeText1: { type: String },
      wBSCloseCancelDelete16px1: { type: String },
      badgeText2: { type: String },
      wBSCloseCancelDelete16px2: { type: String },
      buttonText: { type: String },
    },
  });
</script>
