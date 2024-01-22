<template>
  <div
    class="w-full relative overflow-hidden flex flex-col items-start justify-start tracking-[normal]"
  >
    <header />
    <section
      class="self-stretch bg-base-white overflow-hidden flex flex-col items-center justify-start p-2.5 gap-[20px] text-left text-base text-primary-main-1 font-roboto-mono"
    >
      <h1
        class="m-0 self-stretch h-[53px] relative text-21xl uppercase font-medium font-inherit inline-block pl-5 pr-5 mq950:text-13xl mq450:text-5xl"
      >
        UXUI Designer
      </h1>
      <div class="self-stretch relative font-medium pl-5 pr-5">
        <span>Linkdn |</span>
        <span class="text-salmon"> Xing</span>
      </div>
      <div class="self-stretch h-[42px] relative inline-block pl-5 pr-5">
        Experience the difference that a user-centric design mindset, a custom
        design system, and coding finesse in diverse frameworks can make in your
        projects.
      </div>
    </section>
    <MyRecentWork /><Contact />
    <section
      class="self-stretch bg-primary-main-1 overflow-hidden flex flex-col items-center justify-start p-10 gap-[20px] text-left text-21xl text-base-white font-roboto-mono"
    >
      <h1
        class="m-0 self-stretch h-[53px] relative text-inherit uppercase font-medium font-inherit inline-block mq950:text-13xl mq450:text-5xl"
      >
        Empowering Your Vison with Functionality
      </h1>
      <footer
        class="self-stretch h-[42px] flex flex-row items-start justify-start text-left text-base text-base-white font-roboto-mono"
      >
        <div class="self-stretch relative">
          <p class="m-0">
            By the way, I built the Portfolio from scratch with Vue JS,
            Tailwind, Node JS.
          </p>
          <p class="m-0">https://github.com/Kano85</p>
        </div>
      </footer>
    </section>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import Header from "../components/Header.vue";
  import MyRecentWork from "../components/MyRecentWork.vue";
  import Contact from "../components/Contact.vue";

  export default defineComponent({
    name: "Portfolio",
    components: { Header, MyRecentWork, Contact },
  });
</script>
