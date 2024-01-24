<template>
  <div
    class="w-[501px] flex flex-col items-start justify-start pt-5 px-0 pb-0 box-border min-w-[501px] max-w-full text-left text-base text-white font-roboto-mono mq725:min-w-full mq1000:flex-1"
    :style="logoFrameStyle"
  >
    <div
      class="self-stretch flex flex-col items-start justify-start gap-[10px] max-w-full"
    >
      <div
        class="self-stretch flex flex-row items-start justify-between gap-[20px] text-right mq450:flex-wrap"
      >
        <div
          class="h-[196.6px] w-[155px] overflow-hidden shrink-0 flex flex-col items-start justify-start gap-[41px]"
        >
          <img
            class="self-stretch h-[24.9px] relative max-w-full overflow-hidden shrink-0"
            loading="eager"
            alt=""
            src="/logowhite-1.svg"
          />
          <img
            class="w-[93.2px] flex-1 relative max-h-full"
            loading="eager"
            alt=""
            src="/group-852.svg"
          />
          <img
            class="w-[115.2px] h-[25.5px] relative"
            loading="eager"
            alt=""
            src="/group-851.svg"
          />
        </div>
        <div class="h-[63px] relative inline-block">
          <p class="m-0">
            <b class="font-roboto-mono">User story example:</b>
          </p>
          <p class="m-0">
            <span>&nbsp;</span>
          </p>
          <p class="m-0">
            <a
              class="text-[inherit]"
              href="https://www.figma.com/file/7tKLHo6daiwnPize08vehE/portfolio-research-Figma?type=design&node-id=0-1&mode=design"
              target="_blank"
            >
              <span>
                <span class="[text-decoration:underline]">Figma link</span>
              </span>
            </a>
          </p>
        </div>
      </div>
      <div
        class="self-stretch relative text-sm"
        :style="trainspotIsAContainerStyle"
      >
        <p class="m-0">
          <b class="font-roboto-mono"
            >Trainspot is a tool created by WBS for Mein Bildungsraum
            project. </b
          >
          <span class="font-roboto-mono"
            > Nationwide Digital Learning Initiative: Bridging Education and
            Technology.
          </span>
          <b class="font-roboto-mono">Mein Bildungsraum</b>
          <span>
            vision is to revolutionize digital education across the nation by
            creating an inclusive digital learning space. This collaborative
            project connects learners, educators, and educational services,
            breaking down barriers and fostering a community of shared knowledge
            and growth. </span
          >
        </p>
        <p class="m-0">
          Education providers can seamlessly integrate with our network, joining
          us in shaping the future of digital education. Together, we're not
          just building a platform, but a legacy of learning and innovation.
        </p>
      </div>
      <a
        class="w-[422px] relative [text-decoration:underline] text-[inherit] inline-block max-w-full"
        href="https://www.meinbildungsraum.de/en/"
        target="_blank"
        >https://www.meinbildungsraum.de/en/</a
      >
      <div
        class="self-stretch h-[666px] relative text-sm inline-block"
        :style="uXUIDesignProcessInContainerStyle"
      >
        <p class="m-0">
          <b class="font-roboto-mono">UXUI Design Process</b>
          <span
            >  In the Trainspot project, I embraced the role of a UX/UI designer
            with a focus on empathetic design and agile execution using a common
            design thinking method. Here’s a highlight of my key
            contributions:</span
          >
        </p>
        <p class="m-0">&nbsp;</p>
        <p class="m-0">- Set clear design objectives focused on user needs.</p>
        <p class="m-0">- Identified user profiles through quick interviews.</p>
        <p class="m-0">
          - Explored user interactions for insights into tool improvements.
        </p>
        <p class="m-0">- Documented findings for in-depth analysis.</p>
        <p class="m-0">
          - Analyzed data to detect patterns and define design directions.
        </p>
        <p class="m-0">
          - Prioritized issues based on impact and practicality.
        </p>
        <p class="m-0">
          - Created prototypes and integrated continuous user feedback.
        </p>
        <p class="m-0">&nbsp;</p>
        <p class="m-0">
          <span
            >This approach ensured a user-centered design aligned with our agile
            development process.    </span
          >
          <b class="font-roboto-mono">Agile & Scrum Involvement im project: </b>
        </p>
        <ul class="m-0 text-inherit pl-[19px]">
          <li class="mb-0">
            <span
              >Engaged in Scrum rituals: Sprint Planning, Daily Stand-ups,
              Sprint Reviews, and Retrospectives to adapt and improve our
              product iteratively.</span
            >
          </li>
          <li class="mb-0">
            <span
              >Worked collaboratively with cross-functional teams to refine the
              backlog, ensuring all tasks are well-understood and aligned with
              sprint goals.</span
            >
          </li>
          <li class="mb-0">
            <span
              >Contributed to a unique design system, crafting a dedicated
              component library to ensure consistency and accelerate the design
              process.</span
            >
          </li>
        </ul>
        <p class="m-0">
          This methodical and collaborative approach underpins our agile
          mindset, driving the project towards success with each sprint.
        </p>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import type * as CSS from "csstype";

  export default defineComponent({
    name: "LogoFrame",
    props: {
      figmaLinkWidth: { type: [Object, Array, String, Number, Boolean] },
      figmaLinkMinWidth: { type: [Object, Array, String, Number, Boolean] },
      figmaLinkFlex: { type: String },
      inTheTrainspotHeight: { type: [Object, Array, String, Number, Boolean] },
      propHeight: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      logoFrameStyle(): CSS.Properties {
        return {
          width: this.figmaLinkWidth,
          minWidth: this.figmaLinkMinWidth,
          flex: this.figmaLinkFlex,
        };
      },
      trainspotIsAContainerStyle(): CSS.Properties {
        return {
          height: this.inTheTrainspotHeight,
        };
      },
      uXUIDesignProcessInContainerStyle(): CSS.Properties {
        return {
          height: this.propHeight,
        };
      },
    },
  });
</script>
