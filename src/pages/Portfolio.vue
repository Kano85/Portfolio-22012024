<template>
  <div
    class="w-full relative overflow-hidden flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[0.06rem] box-border tracking-[normal]"
  >
    <header />
    <section
      class="self-stretch bg-white overflow-hidden flex flex-col items-center justify-start p-[1.25rem] gap-[1.25rem] shrink-0 text-left text-[1rem] text-primary-main-1 font-roboto-mono"
      data-scroll-to="about"
    >
      <h1
        class="m-0 self-stretch h-[3.31rem] relative text-[2.5rem] uppercase font-medium font-inherit inline-block mq925:text-[2rem] mq450:text-[1.5rem]"
      >
        UXUI Designer
      </h1>
      <div
        class="self-stretch flex flex-row items-start justify-start py-[0rem] px-[1.25rem]"
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
      <div class="self-stretch h-[2.63rem] relative inline-block">
        Experience the difference that a user-centric design mindset, a custom
        design system, and coding finesse in diverse frameworks can make in your
        projects.
      </div>
    </section>
    <MyRecentWork /><Contact />
    <footer
      class="self-stretch bg-primary-main-1 overflow-hidden flex flex-col items-center justify-start p-[1.25rem] box-border gap-[1.25rem] min-h-[15.81rem] max-w-full shrink-0 text-left text-[2.5rem] text-white font-roboto-mono"
    >
      <h1
        class="m-0 self-stretch h-[3.31rem] relative text-inherit uppercase font-medium font-inherit inline-block mq925:text-[2rem] mq450:text-[1.5rem]"
      >
        Empowering Your Vison with Functionality
      </h1>
      <div
        class="self-stretch flex flex-row items-start justify-between py-[0rem] px-[1.25rem] box-border gap-[1.25rem] max-w-full text-[1rem] mq925:flex-wrap"
      >
        <div class="h-[2.63rem] relative inline-block max-w-full">
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
          class="h-[3.74rem] w-[3.74rem] relative cursor-pointer"
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
