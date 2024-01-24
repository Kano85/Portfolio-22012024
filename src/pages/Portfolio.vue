<template>
  <div
    class="w-full relative overflow-hidden flex flex-col items-start justify-start pt-0 px-0 pb-px box-border tracking-[normal]"
  >
    <header />
    <section
      class="self-stretch bg-white overflow-hidden flex flex-col items-center justify-start p-5 gap-[20px] shrink-0 text-left text-base text-primary-main-1 font-roboto-mono"
      data-scroll-to="about"
    >
      <h1
        class="m-0 self-stretch h-[53px] relative text-21xl uppercase font-medium font-inherit inline-block mq925:text-13xl mq450:text-5xl"
      >
        UXUI Designer
      </h1>
      <div
        class="self-stretch flex flex-row items-start justify-start py-0 px-5"
      >
        <div class="relative font-medium">
          <a
            class="text-[inherit]"
            href="https://de.linkedin.com/"
            target="_blank"
          >
            <span>
              <span class="[text-decoration:underline]">Linkedln</span>
            </span>
          </a>
          <span> | </span>
          <a
            class="text-[inherit]"
            href="https://www.xing.com/profile/Harold_Cano"
            target="_blank"
          >
            <span>
              <span class="[text-decoration:underline]">Xing</span>
            </span>
          </a>
          <span> | </span>
          <span class="text-salmon">CV PDF</span>
        </div>
      </div>
      <div class="self-stretch h-[42px] relative inline-block">
        Experience the difference that a user-centric design mindset, a custom
        design system, and coding finesse in diverse frameworks can make in your
        projects.
      </div>
    </section>
    <MyRecentWork /><Contact />
    <footer
      class="self-stretch bg-primary-main-1 overflow-hidden flex flex-col items-center justify-start p-5 box-border gap-[20px] min-h-[253px] max-w-full shrink-0 text-left text-21xl text-white font-roboto-mono"
    >
      <h1
        class="m-0 self-stretch h-[53px] relative text-inherit uppercase font-medium font-inherit inline-block mq925:text-13xl mq450:text-5xl"
      >
        Empowering Your Vison with Functionality
      </h1>
      <div
        class="self-stretch flex flex-row items-start justify-between py-0 px-5 box-border gap-[20px] max-w-full text-base mq925:flex-wrap"
      >
        <div class="h-[42px] relative inline-block max-w-full">
          <p class="m-0">
            By the way, I built the Portfolio from scratch with Vue JS,
            Tailwind, Node JS.
          </p>
          <p class="m-0">
            <a
              class="text-[inherit]"
              href="https://github.com/Kano85"
              target="_blank"
            >
              <span class="[text-decoration:underline]"
                >https://github.com/Kano85</span
              >
            </a>
          </p>
        </div>
        <img
          class="h-[59.8px] w-[59.8px] relative cursor-pointer"
          loading="eager"
          alt=""
          src="/group-854.svg"
          :onClick="onGroupClick"
        />
      </div>
    </footer>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import Header from "../components/Header.vue";
  import MyRecentWork from "../components/MyRecentWork.vue";
  import Contact from "../components/Contact.vue";

  export default defineComponent({
    name: "Portfolio",
    components: { Header, MyRecentWork, Contact },
    methods: {
      onGroupClick() {
        const anchor = document.querySelector("[data-scroll-to='header']");
        if (anchor) {
          anchor.scrollIntoView({ block: "start", behavior: "smooth" });
        }
      },
    },
  });
</script>
