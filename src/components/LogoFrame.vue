<template>
  <div
    class="w-[31.31rem] flex flex-col items-start justify-start pt-[1.25rem] px-[0rem] pb-[0rem] box-border min-w-[31.31rem] max-w-full text-left text-[1rem] text-white font-roboto-mono mq1000:flex-1 mq725:min-w-full"
    :style="logoFrameStyle"
  >
    <div
      class="self-stretch flex flex-col items-start justify-start gap-[0.63rem] max-w-full"
    >
      <div
        class="self-stretch flex flex-row items-start justify-between gap-[1.25rem] text-right mq450:flex-wrap"
      >
        <div
          class="h-[12.29rem] w-[9.69rem] overflow-hidden shrink-0 flex flex-col items-start justify-start gap-[2.56rem]"
        >
          <img
            class="self-stretch h-[1.56rem] relative max-w-full overflow-hidden shrink-0"
            loading="eager"
            alt=""
            src="/logowhite-1.svg"
          />
          <img
            class="w-[5.83rem] flex-1 relative max-h-full"
            loading="eager"
            alt=""
            src="/group-852.svg"
          />
          <img
            class="w-[7.2rem] h-[1.59rem] relative"
            loading="eager"
            alt=""
            src="/group-851.svg"
          />
        </div>
        <div class="h-[3.94rem] relative inline-block">
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
        class="self-stretch relative text-[0.88rem]"
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
        class="w-[26.38rem] relative [text-decoration:underline] text-[inherit] inline-block max-w-full"
        href="https://www.meinbildungsraum.de/en/"
        target="_blank"
        >https://www.meinbildungsraum.de/en/</a
      >
      <div
        class="self-stretch h-[41.63rem] relative text-[0.88rem] inline-block"
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
        <ul class="m-0 text-inherit pl-[1.36rem]">
          <li class="mb-[false]">
            <span
              >Engaged in Scrum rituals: Sprint Planning, Daily Stand-ups,
              Sprint Reviews, and Retrospectives to adapt and improve our
              product iteratively.</span
            >
          </li>
          <li class="mb-[false]">
            <span
              >Worked collaboratively with cross-functional teams to refine the
              backlog, ensuring all tasks are well-understood and aligned with
              sprint goals.</span
            >
          </li>
          <li class="mb-[false]">
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
<script>
  import { defineComponent } from "vue";

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
      logoFrameStyle() {
        return {
          width: this.figmaLinkWidth,
          minWidth: this.figmaLinkMinWidth,
          flex: this.figmaLinkFlex,
        };
      },
      trainspotIsAContainerStyle() {
        return {
          height: this.inTheTrainspotHeight,
        };
      },
      uXUIDesignProcessInContainerStyle() {
        return {
          height: this.propHeight,
        };
      },
    },
  });
</script>
