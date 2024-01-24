<template>
  <div
    class="w-full relative bg-primary-main-1 overflow-hidden flex flex-col items-center justify-start py-[60px] px-5 box-border gap-[10px] tracking-[normal] text-left text-base text-white font-roboto-mono"
  >
    <NavigationBar />
    <main
      class="w-[1201px] flex flex-row items-start justify-start gap-[81px] max-w-full shrink-0 mq1000:flex-wrap mq725:gap-[40px] mq450:gap-[20px]"
    >
      <div
        class="flex-1 flex flex-col items-start justify-start pt-0 px-0 pb-0 box-border gap-[40px] min-w-[402px] max-w-full mq725:gap-[20px] mq725:min-w-full"
      >
        <img
          class="self-stretch h-[414px] relative max-w-full overflow-hidden shrink-0 object-cover"
          loading="eager"
          alt=""
          src="/frame-594@2x.png"
        />
        <img
          class="self-stretch h-[420.3px] relative max-w-full overflow-hidden shrink-0 object-cover"
          loading="eager"
          alt=""
          src="/frame-595@2x.png"
        />
        <img
          class="self-stretch h-[610.2px] relative max-w-full overflow-hidden shrink-0 object-cover"
          loading="eager"
          alt=""
          src="/frame-596@2x.png"
        />
        <img
          class="self-stretch h-[610.2px] relative max-w-full overflow-hidden shrink-0 object-cover"
          loading="eager"
          alt=""
          src="/frame-597@2x.png"
        />
      </div>
      <LogoFrame
        figmaLinkWidth="501px"
        figmaLinkMinWidth="501px"
        propHeight="666px"
      />
    </main>
    <div
      class="self-stretch flex flex-row items-center justify-between py-0 px-2.5 box-border gap-[20px] max-w-full mq725:flex-wrap"
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
  import NavigationBar from "../components/NavigationBar.vue";
  import LogoFrame from "../components/LogoFrame.vue";

  export default defineComponent({
    name: "Page1",
    components: { NavigationBar, LogoFrame },
    methods: {
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
