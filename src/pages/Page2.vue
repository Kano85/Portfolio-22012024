<template>
  <div
    class="w-full relative bg-primary-main-1 overflow-hidden flex flex-col items-center justify-start py-[60px] px-5 box-border gap-[10px] tracking-[normal] text-left text-base text-white font-roboto-mono"
  >
    <div
      class="flex flex-row items-center justify-start gap-[12px] max-w-full lg:flex-wrap"
      data-scroll-to="headerContainer"
    >
      <img
        class="h-6 w-6 relative object-contain cursor-pointer"
        loading="eager"
        alt=""
        src="/wbs-arrow@2x.png"
        @click="onWBSArrowIconClick"
      />
      <div
        class="w-[82px] flex flex-col items-start justify-start pt-0 px-0 pb-[3px] box-border"
      >
        <div class="w-[46px] relative font-medium inline-block">Back</div>
      </div>
      <img
        class="h-6 w-6 relative cursor-pointer"
        loading="eager"
        alt=""
        src="/wbs-arrow-1.svg"
        @click="onWBSArrowIcon1Click"
      />
      <div
        class="w-[251px] flex flex-col items-start justify-start pt-0 px-0 pb-[3px] box-border"
      >
        <div
          class="self-stretch flex flex-row items-start justify-between gap-[20px]"
        >
          <div class="relative font-medium">Trainspot</div>
          <div class="relative font-medium">Kursplannung</div>
        </div>
      </div>
      <div
        class="w-[278px] flex flex-col items-start justify-start py-5 px-0 box-border"
      >
        <img
          class="w-6 h-6 relative cursor-pointer"
          loading="eager"
          alt=""
          src="/wbs-arrow-2.svg"
          @click="onWBSArrowIcon2Click"
        />
      </div>
      <h1
        class="m-0 h-[66px] relative text-31xl uppercase font-bold font-inherit inline-block max-w-full mq450:text-11xl mq1050:text-21xl"
      >
        Kurskonfigurator
      </h1>
    </div>
    <main
      class="w-[1200px] flex flex-row items-start justify-start gap-[80px] max-w-full shrink-0 lg:gap-[40px] mq750:gap-[20px] mq1050:flex-wrap"
    >
      <div
        class="w-[528px] flex flex-col items-start justify-start pt-0 px-0 pb-0 box-border gap-[60px] min-w-[528px] max-w-full mq750:gap-[30px] mq750:min-w-full mq1050:flex-1"
      >
        <div
          class="self-stretch flex flex-row items-start justify-start gap-[40px] mq450:flex-wrap mq750:gap-[20px]"
        >
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[159px] min-h-[527px]"
            loading="eager"
            alt=""
            src="/11-1@2x.png"
          />
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[159px] min-h-[529px]"
            loading="eager"
            alt=""
            src="/20@2x.png"
          />
        </div>
        <div
          class="self-stretch overflow-hidden flex flex-row items-start justify-start gap-[40px] mq450:flex-wrap mq750:gap-[20px]"
        >
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[159px] min-h-[529px]"
            loading="eager"
            alt=""
            src="/5@2x.png"
          />
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[159px] min-h-[529px]"
            loading="eager"
            alt=""
            src="/ak3@2x.png"
          />
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-start gap-[40px] mq450:flex-wrap mq750:gap-[20px]"
        >
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[159px] min-h-[528px]"
            loading="eager"
            alt=""
            src="/frame-853@2x.png"
          />
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[159px] min-h-[528px]"
            loading="eager"
            alt=""
            src="/mask-group@2x.png"
          />
        </div>
        <div
          class="self-stretch overflow-hidden flex flex-row items-start justify-start gap-[40px] mq450:flex-wrap mq750:gap-[20px]"
        >
          <img
            class="h-[528.2px] flex-1 relative max-w-full overflow-hidden object-cover min-w-[159px]"
            loading="eager"
            alt=""
            src="/13@2x.png"
          />
          <img
            class="h-[517.6px] flex-1 relative max-w-full overflow-hidden object-cover min-w-[159px]"
            loading="eager"
            alt=""
            src="/frame-81@2x.png"
          />
        </div>
      </div>
      <LogoFrame
        figmaLinkWidth="unset"
        figmaLinkMinWidth="385px"
        figmaLinkFlex="1"
        inTheTrainspotHeight="216px"
        propHeight="576px"
      />
    </main>
    <div
      class="self-stretch flex flex-row items-center justify-between py-0 px-2.5 box-border gap-[20px] max-w-full mq750:flex-wrap"
    >
      <div class="h-[42px] flex flex-row items-center justify-start max-w-full">
        <div
          class="self-stretch flex flex-row items-start justify-end max-w-full"
        >
          <div class="self-stretch relative font-medium">
            <p class="m-0">Do you want to see more about this project ?</p>
            <p class="m-0">
              <a
                class="text-[inherit]"
                href="https://www.figma.com/file/7tKLHo6daiwnPize08vehE/portfolio-research-Figma?type=design&node-id=0-1&mode=design"
                target="_blank"
              >
                <span class="[text-decoration:underline]"
                  >Figma link to the Mockups
                </span>
              </a>
            </p>
          </div>
        </div>
      </div>
      <img
        class="h-[59.8px] w-[59.8px] relative cursor-pointer"
        loading="eager"
        alt=""
        src="/group-854.svg"
        :onClick="onGroupClick"
      />
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import LogoFrame from "../components/LogoFrame.vue";

  export default defineComponent({
    name: "Page2",
    components: { LogoFrame },
    methods: {
      onWBSArrowIconClick() {
        this.$router.push("/portfolio20012024");
      },
      onWBSArrowIcon1Click() {
        this.$router.push("/page120012024");
      },
      onWBSArrowIcon2Click() {
        this.$router.push("/page120012024");
      },
      onGroupClick() {
        const anchor = document.querySelector(
          "[data-scroll-to='headerContainer']"
        );
        if (anchor) {
          anchor.scrollIntoView({ block: "start", behavior: "smooth" });
        }
      },
    },
  });
</script>
