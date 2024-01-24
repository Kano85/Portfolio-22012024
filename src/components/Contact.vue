<template>
  <section
    class="self-stretch h-[16.84rem] bg-white overflow-hidden shrink-0 flex flex-col items-end justify-start py-[1.25rem] px-[2.5rem] box-border max-w-full text-left text-[3.59rem] text-primary-main-1 font-roboto-mono"
    data-scroll-to="contact"
  >
    <div
      class="w-[26.94rem] flex-1 flex flex-col items-end justify-start gap-[1.25rem] max-w-full"
    >
      <b
        class="h-[4.75rem] relative uppercase inline-block mq925:text-[2.88rem] mq450:text-[2.13rem]"
        >Contact</b
      >
      <div class="flex-1 relative text-[1rem] tracking-[0.01em] text-right">
        <p class="m-0">Gleimstrasse 3</p>
        <p class="m-0">13355 Berlin</p>
        <p class="m-0">hcanocardenas@gmail.com</p>
        <p class="m-0">+4917627744274</p>
      </div>
      <div class="flex flex-row items-start justify-start gap-[1.23rem]">
        <img
          class="h-[1.84rem] w-[1.84rem] relative overflow-hidden shrink-0 min-h-[1.88rem] cursor-pointer"
          loading="eager"
          alt=""
          src="/discord.svg"
          :onClick="onDiscordIconClick"
        />
        <img
          class="h-[1.84rem] w-[1.84rem] relative overflow-hidden shrink-0 min-h-[1.88rem] cursor-pointer"
          loading="eager"
          alt=""
          src="/facebook.svg"
          :onClick="onFacebookIconClick"
        />
        <img
          class="h-[1.84rem] w-[1.84rem] relative overflow-hidden shrink-0 min-h-[1.88rem] cursor-pointer"
          loading="eager"
          alt=""
          src="/dribbble.svg"
          :onClick="onDribbbleIconClick"
        />
        <img
          class="h-[1.84rem] w-[1.84rem] relative overflow-hidden shrink-0 min-h-[1.88rem] cursor-pointer"
          loading="eager"
          alt=""
          src="/nstagram.svg"
          :onClick="onNstagramIconClick"
        />
        <img
          class="h-[1.84rem] w-[1.84rem] relative overflow-hidden shrink-0 min-h-[1.88rem] cursor-pointer"
          loading="eager"
          alt=""
          src="/behance.svg"
          :onClick="onBehanceIconClick"
        />
      </div>
    </div>
  </section>
</template>
<script>
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
