<template>
  <div
    class="self-stretch flex flex-row flex-wrap items-start justify-center gap-[12.02px] text-left text-6xs text-primary-main-1 font-source-sans-pro"
  >
    <div
      class="flex-1 rounded-[4.01px] bg-base-white flex flex-col items-start justify-start p-[6.009865760803223px] box-border min-w-[157px] whitespace-nowrap"
    >
      <div
        class="self-stretch h-[86.1px] relative leading-[140%] inline-block shrink-0"
        :style="kompetenzorientierungBeziehuStyle"
      >
        <p class="m-0">
          <b class="tracking-[0.05px]">Kompetenzorientierung:</b>
        </p>
        <ul class="m-0 text-inherit pl-[9px]">
          <li class="mb-0">
            <span class="tracking-[0.09px]">Beziehungsmanagement</span>
          </li>
          <li class="mb-0">
            <span class="tracking-[0.09px]">Kommunikationsfähigkeit</span>
          </li>
          <li class="mb-0">
            <span class="tracking-[0.09px]"
              >Lern- und Veränderungsbereitschaft</span
            >
          </li>
          <li class="mb-0">
            <span class="tracking-[0.09px]">Teamfähigkeit</span>
          </li>
          <li class="mb-0">
            <span class="tracking-[0.09px]">Zielorientierung </span>
          </li>
        </ul>
        <p class="m-0">
          <b class="tracking-[0.05px]">Methoden:</b>
        </p>
        <ul class="m-0 text-inherit pl-[9px]">
          <li class="mb-0">
            <span class="tracking-[0.09px]">Input</span>
          </li>
          <li>
            <span class="tracking-[0.09px]">Austausch</span>
          </li>
        </ul>
      </div>
    </div>
    <div
      class="flex-1 rounded-[4.01px] bg-base-white flex flex-col items-start justify-start p-[6.009865760803223px] box-border min-w-[157px] whitespace-nowrap"
    >
      <div class="self-stretch h-[110px] relative leading-[140%] inline-block">
        <p class="m-0">
          <b class="tracking-[0.05px]">Trainingsdauer:</b>
        </p>
        <p class="m-0 tracking-[0.09px]">
          90 Minuten, 16:00 Uhr bis 17:30 Uhr 
        </p>
        <p class="m-0">
          <b class="tracking-[0.05px]">Maximale Anzahl der Teilnehmer:</b>
        </p>
        <p class="m-0 tracking-[0.09px]">15</p>
        <p class="m-0">
          <b class="tracking-[0.05px]">Teilnahmebescheinigung:</b>
        </p>
        <p class="m-0 tracking-[0.09px]">
          Du erhältst eine Teilnahmebescheinigung.
        </p>
        <p class="m-0 tracking-[0.09px]">&nbsp;</p>
        <p class="m-0">
          <b class="tracking-[0.05px]">Trainer:in</b>
        </p>
        <p class="m-0 tracking-[0.09px]">Monika Lamprecht</p>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import type * as CSS from "csstype";

  export default defineComponent({
    name: "NavLine",
    props: {
      propHeight: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      kompetenzorientierungBeziehuStyle(): CSS.Properties {
        return {
          height: this.propHeight,
        };
      },
    },
  });
</script>
