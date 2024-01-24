<template>
  <div
    class="w-full relative bg-primary-main-1 overflow-hidden flex flex-col items-center justify-start py-[3.75rem] px-[1.25rem] box-border gap-[0.63rem] tracking-[normal] text-left text-[1rem] text-white font-roboto-mono"
  >
    <div
      class="flex flex-row items-center justify-start gap-[0.75rem] max-w-full lg:flex-wrap"
      data-scroll-to="headerContainer"
    >
      <img
        class="h-[1.5rem] w-[1.5rem] relative object-contain cursor-pointer"
        loading="eager"
        alt=""
        src="/wbs-arrow@2x.png"
        @click="onWBSArrowIconClick"
      />
      <div
        class="w-[5.13rem] flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[0.19rem] box-border"
      >
        <div class="w-[2.88rem] relative font-medium inline-block">Back</div>
      </div>
      <img
        class="h-[1.5rem] w-[1.5rem] relative cursor-pointer"
        loading="eager"
        alt=""
        src="/wbs-arrow-1.svg"
        @click="onWBSArrowIcon1Click"
      />
      <div
        class="w-[15.69rem] flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[0.19rem] box-border"
      >
        <div
          class="self-stretch flex flex-row items-start justify-between gap-[1.25rem]"
        >
          <div class="relative font-medium">Trainspot</div>
          <div class="relative font-medium">Kursplannung</div>
        </div>
      </div>
      <div
        class="w-[17.38rem] flex flex-col items-start justify-start py-[1.25rem] px-[0rem] box-border"
      >
        <img
          class="w-[1.5rem] h-[1.5rem] relative cursor-pointer"
          loading="eager"
          alt=""
          src="/wbs-arrow-2.svg"
          @click="onWBSArrowIcon2Click"
        />
      </div>
      <h1
        class="m-0 h-[4.13rem] relative text-[3.13rem] uppercase font-bold font-inherit inline-block max-w-full mq450:text-[1.88rem] mq1050:text-[2.5rem]"
      >
        Kurskonfigurator
      </h1>
    </div>
    <main
      class="w-[75rem] flex flex-row items-start justify-start gap-[5rem] max-w-full shrink-0 lg:gap-[2.5rem] mq750:gap-[1.25rem] mq1050:flex-wrap"
    >
      <div
        class="w-[33rem] flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[0rem] box-border gap-[3.75rem] min-w-[33rem] max-w-full mq750:gap-[1.88rem] mq750:min-w-full mq1050:flex-1"
      >
        <div
          class="self-stretch flex flex-row items-start justify-start gap-[2.5rem] mq450:flex-wrap mq750:gap-[1.25rem]"
        >
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[9.94rem] min-h-[32.94rem]"
            loading="eager"
            alt=""
            src="/11-1@2x.png"
          />
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[9.94rem] min-h-[33.06rem]"
            loading="eager"
            alt=""
            src="/20@2x.png"
          />
        </div>
        <div
          class="self-stretch overflow-hidden flex flex-row items-start justify-start gap-[2.5rem] mq450:flex-wrap mq750:gap-[1.25rem]"
        >
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[9.94rem] min-h-[33.06rem]"
            loading="eager"
            alt=""
            src="/5@2x.png"
          />
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[9.94rem] min-h-[33.06rem]"
            loading="eager"
            alt=""
            src="/ak3@2x.png"
          />
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-start gap-[2.5rem] mq450:flex-wrap mq750:gap-[1.25rem]"
        >
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[9.94rem] min-h-[33rem]"
            loading="eager"
            alt=""
            src="/frame-853@2x.png"
          />
          <img
            class="self-stretch flex-1 relative max-w-full overflow-hidden max-h-full object-cover min-w-[9.94rem] min-h-[33rem]"
            loading="eager"
            alt=""
            src="/mask-group@2x.png"
          />
        </div>
        <div
          class="self-stretch overflow-hidden flex flex-row items-start justify-start gap-[2.5rem] mq450:flex-wrap mq750:gap-[1.25rem]"
        >
          <img
            class="h-[33.01rem] flex-1 relative max-w-full overflow-hidden object-cover min-w-[9.94rem]"
            loading="eager"
            alt=""
            src="/13@2x.png"
          />
          <img
            class="h-[32.35rem] flex-1 relative max-w-full overflow-hidden object-cover min-w-[9.94rem]"
            loading="eager"
            alt=""
            src="/frame-81@2x.png"
          />
        </div>
      </div>
      <LogoFrame
        figmaLinkWidth="unset"
        figmaLinkMinWidth="24.06rem"
        figmaLinkFlex="1"
        inTheTrainspotHeight="13.5rem"
        propHeight="36rem"
      />
    </main>
    <div
      class="self-stretch flex flex-row items-center justify-between py-[0rem] px-[0.63rem] box-border gap-[1.25rem] max-w-full mq750:flex-wrap"
    >
      <div
        class="h-[2.63rem] flex flex-row items-center justify-start max-w-full"
      >
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
        class="h-[3.74rem] w-[3.74rem] relative cursor-pointer"
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
