<template>
  <section
    class="self-stretch h-[269.5px] bg-white overflow-hidden shrink-0 flex flex-col items-end justify-start py-5 px-10 box-border max-w-full text-left text-38xl-4 text-primary-main-1 font-roboto-mono"
    data-scroll-to="contact"
  >
    <div
      class="w-[431px] flex-1 flex flex-col items-end justify-start gap-[20px] max-w-full"
    >
      <b
        class="h-[76px] relative uppercase inline-block mq450:text-15xl mq925:text-27xl"
        >Contact</b
      >
      <div class="flex-1 relative text-base tracking-[0.01em] text-right">
        <p class="m-0">Gleimstrasse 3</p>
        <p class="m-0">13355 Berlin</p>
        <p class="m-0">hcanocardenas@gmail.com</p>
        <p class="m-0">+4917627744274</p>
      </div>
      <div class="flex flex-row items-start justify-start gap-[19.68px]">
        <img
          class="h-[29.5px] w-[29.5px] relative overflow-hidden shrink-0 min-h-[30px] cursor-pointer"
          loading="eager"
          alt=""
          src="/discord.svg"
          :onClick="onDiscordIconClick"
        />
        <img
          class="h-[29.5px] w-[29.5px] relative overflow-hidden shrink-0 min-h-[30px] cursor-pointer"
          loading="eager"
          alt=""
          src="/facebook.svg"
          :onClick="onFacebookIconClick"
        />
        <img
          class="h-[29.5px] w-[29.5px] relative overflow-hidden shrink-0 min-h-[30px] cursor-pointer"
          loading="eager"
          alt=""
          src="/dribbble.svg"
          :onClick="onDribbbleIconClick"
        />
        <img
          class="h-[29.5px] w-[29.5px] relative overflow-hidden shrink-0 min-h-[30px] cursor-pointer"
          loading="eager"
          alt=""
          src="/nstagram.svg"
          :onClick="onNstagramIconClick"
        />
        <img
          class="h-[29.5px] w-[29.5px] relative overflow-hidden shrink-0 min-h-[30px] cursor-pointer"
          loading="eager"
          alt=""
          src="/behance.svg"
          :onClick="onBehanceIconClick"
        />
      </div>
    </div>
  </section>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Contact",
    methods: {
      onDiscordIconClick() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onFacebookIconClick() {
        window.open("https://www.facebook.com/animaapp/");
      },
      onDribbbleIconClick() {
        window.open("https://dribbble.com/animaapp");
      },
      onNstagramIconClick() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onBehanceIconClick() {
        window.open("https://www.behance.net/Anima_design");
      },
    },
  });
</script>
