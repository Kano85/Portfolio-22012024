<template>
  <section
    class="self-stretch bg-base-white flex flex-row items-center justify-center relative gap-[10px] max-w-full text-left text-21xl text-primary-main-1 font-roboto-mono"
  >
    <img
      class="h-full w-full absolute my-0 mx-[!important] top-[0px] right-[0px] bottom-[0px] left-[0px] max-w-full overflow-hidden max-h-full object-cover"
      loading="eager"
      alt=""
      src="/main-1@2x.png"
    />
    <div
      class="flex-1 flex flex-row flex-wrap items-start justify-start pt-[30px] px-10 pb-2.5 box-border [row-gap:20px] max-w-full z-[1]"
    >
      <div
        class="flex-1 overflow-hidden flex flex-col items-start justify-start gap-[269px] min-w-[619px] max-w-full mq950:min-w-full mq700:gap-[67px] mq975:gap-[134px]"
      >
        <h1
          class="m-0 w-[97px] h-[53px] relative text-inherit font-medium font-inherit inline-block mq950:text-13xl mq450:text-5xl"
        >
          Hi !
        </h1>
        <b
          class="self-stretch h-[238px] relative uppercase inline-block text-71xl mq950:text-26xl mq450:text-8xl"
        >
          <p class="m-0">Harold</p>
          <p class="m-0">
            <span>Cano</span>
            <span class="text-70xl-4"> </span>
          </p>
        </b>
      </div>
      <div
        class="w-[247px] flex flex-row flex-wrap items-start justify-start py-0 pr-[3px] pl-0 box-border gap-[29px] text-base"
      >
        <div
          class="w-[59px] relative font-medium inline-block whitespace-nowrap"
        >
          Home
        </div>
        <div
          class="w-[59px] relative font-medium inline-block whitespace-nowrap"
        >
          Works
        </div>
        <div class="w-[68px] relative font-medium inline-block">Contact</div>
      </div>
    </div>
  </section>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Header",
  });
</script>
