<template>
  <div
    class="w-full relative bg-primary-main-1 overflow-hidden flex flex-col items-center justify-start pt-[30px] px-5 pb-[34px] box-border gap-[20px] tracking-[normal]"
  >
    <NavigationBar />
    <form
      class="m-0 self-stretch h-[578px] overflow-y-auto shrink-0 flex flex-col items-start justify-start gap-[40px] max-w-full mq750:gap-[20px] mq1100:h-auto"
    >
      <ContentComparison />
      <div
        class="w-[648px] shadow-[0px_0px_20px_rgba(0,_0,_0,_0.07)] overflow-hidden shrink-0 flex flex-row items-start justify-start max-w-full"
      >
        <div
          class="flex-1 bg-base-white overflow-hidden flex flex-row items-start justify-start max-w-full"
        >
          <div
            class="h-[638px] w-[131px] bg-base-white shadow-[0px_1.5px_7.1px_1.01px_rgba(0,_0,_0,_0.12),_0px_4.1px_5.07px_0.51px_rgba(0,_0,_0,_0.14),_0px_2.5px_2.54px_-1.52px_rgba(0,_0,_0,_0.2)] overflow-hidden shrink-0 flex flex-col items-end justify-start pt-[67px] px-0 pb-0 box-border relative gap-[28px] mq450:hidden mq750:pt-11 mq750:box-border"
          >
            <img
              class="w-[28.9px] h-[30.4px] absolute my-0 mx-[!important] top-[16.2px] right-[51px]"
              loading="eager"
              alt=""
              src="/wbs-logo-1.svg"
            />
            <div
              class="self-stretch h-[17px] flex flex-col items-center justify-start gap-[4px]"
            >
              <b
                class="relative text-smi-2 tracking-[0.13px] leading-[110%] font-source-sans-pro text-secondary-dark-grey-900 text-center"
              >
                <span class="uppercase">T</span>
                <span class="capitalize">rainspot</span>
              </b>
              <div
                class="self-stretch h-[0.51px] relative box-border border-t-[0.5px] border-solid border-base-background"
              />
            </div>
            <frame
              wBSDASH="/wbsdash-1.svg"
              icon2="/icon-2-3.svg"
              wBSList24px="/wbs--list-24px.svg"
              propFlex="1"
              propWidth="118px"
            />
            <div
              class="w-0.5 h-[18.3px] relative rounded-[12.69px] bg-primary-main-1 hidden z-[3]"
            />
            <div
              class="w-[122.3px] h-4 hidden flex-row items-start justify-start gap-[8.12px] z-[4]"
            >
              <img
                class="h-[13.2px] w-[13.2px] relative"
                alt=""
                src="/icon-2-4.svg"
              />
              <b
                class="self-stretch flex-1 relative text-3xs-1 tracking-[-0.02em] leading-[15.22px] font-dm-sans text-base-silver text-left shrink-0"
                >Assessments</b
              >
              <div
                class="h-[18.3px] w-0.5 relative rounded-[12.69px] bg-primary-main-1 hidden"
              />
            </div>
            <div
              class="w-[122.3px] h-4 hidden flex-row items-start justify-start gap-[8.12px] z-[5]"
            >
              <img
                class="h-[13.2px] w-[13.2px] relative"
                alt=""
                src="/icon-2-5.svg"
              />
              <b
                class="self-stretch flex-1 relative text-3xs-1 tracking-[-0.02em] leading-[15.22px] font-dm-sans text-base-silver text-left shrink-0"
                >Bildungsreise</b
              >
              <div
                class="h-[18.3px] w-0.5 relative rounded-[12.69px] bg-primary-main-1 hidden"
              />
            </div>
            <NavFooter logosWBSMedium="/logos--wbs--medium-1.svg" />
          </div>
          <div
            class="flex-1 flex flex-col items-center justify-center max-w-[calc(100%_-_131px)] mq450:max-w-full"
          >
            <div
              class="self-stretch bg-whitesmoke-100 flex flex-col items-start justify-center relative max-w-full"
            >
              <div
                class="self-stretch bg-base-white flex flex-row items-start justify-end py-[2.537074565887451px] px-[9.133467674255371px]"
              >
                <div
                  class="w-[97.5px] overflow-hidden shrink-0 flex flex-row items-center justify-start py-[6.0889787673950195px] pr-[3px] pl-[4.059319019317627px] box-border gap-[12.18px]"
                >
                  <img
                    class="h-[12.2px] w-[12.2px] relative overflow-hidden shrink-0 min-h-[12px]"
                    alt=""
                    src="/filledactionaccountcircle.svg"
                  />
                  <input
                    class="w-[calc(100%_-_19.259319019317626px)] [border:none] [outline:none] font-medium font-roboto text-4xs-1 bg-[transparent] h-[11px] flex-1 relative leading-[10.66px] text-primary-saturated text-left inline-block min-w-[39px]"
                    placeholder="Maximilian Müller"
                    type="text"
                  />
                </div>
              </div>
              <div
                class="self-stretch flex flex-col items-center justify-start p-[12.177957534790039px] box-border gap-[12.18px] min-h-[609px] max-w-full"
              >
                <div
                  class="self-stretch rounded-[4.06px] bg-base-white flex flex-col items-center justify-start p-[4.059319019317627px] box-border gap-[6.09px] max-w-full"
                >
                  <div
                    class="self-stretch overflow-hidden flex flex-row items-center justify-between py-0 pr-[6.0889787673950195px] pl-[9.133467674255371px] gap-[20px] shrink-0 mq750:flex-wrap"
                  >
                    <b
                      class="relative text-smi-2 tracking-[0.13px] leading-[110%] uppercase font-source-sans-pro text-primary-main-1 text-left"
                      >StartKLAR! Grundlagen für das Online-Training</b
                    >
                    <div class="flex flex-row items-center justify-start">
                      <div
                        class="flex flex-col items-start justify-start py-[3.0444893836975098px] pr-[3px] pl-[3.0444893836975098px]"
                      >
                        <img
                          class="w-[12.2px] h-[12.2px] relative"
                          loading="eager"
                          alt=""
                          src="/wbs-arrow-7.svg"
                        />
                      </div>
                      <div
                        class="relative text-4xs-1 leading-[12.18px] font-extrabold font-roboto text-secondary-dark-grey-900 text-left"
                      >
                        frühesten Seminarbeginn
                      </div>
                    </div>
                  </div>
                  <div
                    class="self-stretch flex flex-col items-center justify-start gap-[7.61px] max-w-full shrink-0"
                  >
                    <div
                      class="self-stretch rounded-[6.09px] flex flex-row flex-wrap items-start justify-center py-0 pr-[8.118638038635254px] pl-[4.059319019317627px] box-border [row-gap:20px] max-w-full shrink-0"
                    >
                      <div
                        class="flex-1 flex flex-row items-center justify-start min-w-[289px] max-w-full mq450:gap-[36px]"
                      >
                        <div class="flex flex-row items-center justify-start">
                          <div
                            class="flex flex-col items-start justify-start py-[3.0444893836975098px] pr-[3px] pl-[3.0444893836975098px]"
                          >
                            <img
                              class="w-[12.2px] h-[12.2px] relative"
                              loading="eager"
                              alt=""
                              src="/wbs-arrow-7.svg"
                            />
                          </div>
                          <div
                            class="flex flex-row items-center justify-start gap-[6.09px]"
                          >
                            <b
                              class="relative text-5xs-1 leading-[10.66px] font-roboto text-secondary-dark-grey-900 text-left"
                              >Selbst ist der Lernende – Gestaltung und
                              Organisation von Selbstlernprozessen</b
                            >
                            <div
                              class="flex flex-row items-start justify-start"
                            >
                              <div
                                class="rounded-[5.07px] bg-warning-main flex flex-row items-center justify-center py-0 px-[3.298196792602539px]"
                              >
                                <b
                                  class="relative text-6xs-1 tracking-[0.2px] leading-[10.15px] font-roboto text-base-white text-center"
                                  >Neu</b
                                >
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div
                        class="flex flex-col items-start justify-start py-[4.059319019317627px] px-0 gap-[4.06px]"
                      >
                        <div class="flex flex-row items-start justify-end">
                          <b
                            class="relative text-5xs-1 leading-[10.66px] font-roboto text-primary-main-1 text-left"
                            >15.01.24</b
                          >
                        </div>
                        <div class="flex flex-row items-start justify-end">
                          <b
                            class="relative text-5xs-1 leading-[10.66px] font-roboto text-primary-main-1 text-left"
                            >22.03.24</b
                          >
                        </div>
                      </div>
                    </div>
                    <div
                      class="self-stretch rounded-[6.09px] flex flex-row flex-wrap items-start justify-center py-0 pr-[8.118638038635254px] pl-[4.059319019317627px] box-border [row-gap:20px] max-w-full shrink-0"
                    >
                      <div
                        class="flex-1 flex flex-row items-center justify-start min-w-[189px] max-w-full"
                      >
                        <div
                          class="w-[189.3px] flex flex-row items-center justify-start"
                        >
                          <div
                            class="flex flex-col items-start justify-start py-[3.0444893836975098px] pr-[3px] pl-[3.0444893836975098px]"
                          >
                            <img
                              class="w-[12.2px] h-[12.2px] relative"
                              loading="eager"
                              alt=""
                              src="/wbs-arrow-7.svg"
                            />
                          </div>
                          <div
                            class="h-[11px] flex-1 relative text-5xs-1 leading-[10.66px] font-roboto text-secondary-dark-grey-900 text-left inline-block"
                          >
                            Ausgeglichen im Kursalltag durch innere
                            Zufriedenheit
                          </div>
                        </div>
                      </div>
                      <div
                        class="h-[19.1px] w-[29px] flex flex-col items-start justify-start py-[4.059319019317627px] px-0 box-border"
                      >
                        <div
                          class="self-stretch flex-1 flex flex-row items-start justify-end"
                        >
                          <b
                            class="self-stretch flex-1 relative text-5xs-1 leading-[10.66px] font-roboto text-primary-main-1 text-left"
                            >07.02.24</b
                          >
                        </div>
                      </div>
                    </div>
                    <div
                      class="self-stretch rounded-[6.09px] flex flex-row flex-wrap items-start justify-center py-0 pr-2 pl-1 box-border [row-gap:20px] max-w-full shrink-0"
                    >
                      <div
                        class="flex-1 flex flex-row items-center justify-start min-w-[168px] max-w-full"
                      >
                        <div
                          class="w-[168px] flex flex-row items-center justify-start"
                        >
                          <div
                            class="flex flex-col items-start justify-start py-[3.0444893836975098px] pr-[3px] pl-[3.0444893836975098px]"
                          >
                            <img
                              class="w-[12.2px] h-[12.2px] relative"
                              loading="eager"
                              alt=""
                              src="/wbs-arrow-7.svg"
                            />
                          </div>
                          <div
                            class="h-[11px] flex-1 flex flex-row items-center justify-start gap-[6.09px]"
                          >
                            <b
                              class="self-stretch flex-1 relative text-5xs-1 leading-[10.66px] font-roboto text-secondary-dark-grey-900 text-left"
                              >DSGVO-konforme Arbeit als Dozent/-in</b
                            >
                            <div
                              class="w-[18.6px] flex flex-row items-start justify-start"
                            >
                              <div
                                class="h-[11px] flex-1 rounded-[5.07px] bg-warning-main flex flex-row items-center justify-center py-0 px-[3.298196792602539px] box-border"
                              >
                                <b
                                  class="self-stretch flex-1 relative text-6xs-1 tracking-[0.2px] leading-[10.15px] font-roboto text-base-white text-center"
                                  >Neu</b
                                >
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div
                        class="h-[49.2px] w-[98.8px] flex flex-col items-start justify-start py-[4.059319019317627px] px-0 box-border gap-[4.06px]"
                      >
                        <div
                          class="self-stretch flex-1 flex flex-row items-start justify-end py-0 pr-0 pl-[17px] gap-[12.18px]"
                        >
                          <div
                            class="flex-1 flex flex-row items-start justify-start"
                          >
                            <div
                              class="h-[11px] flex-1 rounded-[5.07px] bg-success-main flex flex-row items-center justify-center py-0 px-[3.298196792602539px] box-border whitespace-nowrap"
                            >
                              <b
                                class="self-stretch flex-1 relative text-6xs-1 tracking-[0.2px] leading-[10.15px] font-roboto text-base-white text-center"
                                >Neue Inhalt</b
                              >
                            </div>
                          </div>
                          <b
                            class="self-stretch w-[29px] relative text-5xs-1 leading-[10.66px] inline-block font-roboto text-primary-main-1 text-left"
                            >25.03.24</b
                          >
                        </div>
                        <div
                          class="self-stretch flex-1 flex flex-row items-start justify-end gap-[12.18px]"
                        >
                          <div
                            class="flex-1 flex flex-row items-start justify-start"
                          >
                            <div
                              class="h-[11px] flex-1 rounded-[5.07px] bg-base-silver flex flex-row items-center justify-center py-0 px-[3.298196792602539px] box-border whitespace-nowrap"
                            >
                              <b
                                class="self-stretch flex-1 relative text-6xs-1 tracking-[0.2px] leading-[10.15px] font-roboto text-base-white whitespace-pre-wrap text-center"
                                >Seminar besucht</b
                              >
                            </div>
                          </div>
                          <b
                            class="self-stretch w-[29px] relative text-5xs-1 leading-[10.66px] inline-block font-roboto text-base-silver text-left"
                            >22.08.23</b
                          >
                        </div>
                        <div
                          class="self-stretch flex-1 flex flex-row items-start justify-end py-0 pr-0 pl-px gap-[12.18px]"
                        >
                          <div
                            class="flex-1 flex flex-row items-start justify-start"
                          >
                            <div
                              class="h-[11px] flex-1 rounded-[5.07px] bg-warning-main flex flex-row items-center justify-center py-0 px-[3.298196792602539px] box-border whitespace-nowrap"
                            >
                              <b
                                class="self-stretch flex-1 relative text-6xs-1 tracking-[0.2px] leading-[10.15px] font-roboto text-base-white text-center"
                                >Seminar gebucht</b
                              >
                            </div>
                          </div>
                          <b
                            class="self-stretch w-[29px] relative text-5xs-1 leading-[10.66px] inline-block font-roboto text-base-silver text-left"
                            >14.03.23</b
                          >
                        </div>
                      </div>
                    </div>
                    <div
                      class="self-stretch rounded-[6.09px] flex flex-row flex-wrap items-start justify-center py-0 px-1 box-border [row-gap:20px] max-w-full shrink-0"
                    >
                      <div
                        class="flex-1 flex flex-row items-center justify-start min-w-[170px] max-w-full"
                      >
                        <div
                          class="w-[170.3px] flex flex-row items-center justify-start"
                        >
                          <div
                            class="flex flex-col items-start justify-start py-[3.0444893836975098px] pr-[3px] pl-[3.0444893836975098px]"
                          >
                            <img
                              class="w-[12.2px] h-[12.2px] relative"
                              alt=""
                              src="/wbs-arrow-7.svg"
                            />
                          </div>
                          <div
                            class="h-[11px] flex-1 relative text-5xs-1 leading-[10.66px] font-roboto text-secondary-dark-grey-900 text-left inline-block"
                          >
                            E-Trainer-Ausbildung: Abschluss mit Lehrproben
                          </div>
                        </div>
                      </div>
                      <div
                        class="h-[18.3px] w-[55.2px] rounded-[2.03px] box-border flex flex-row items-center justify-center py-[3.0444893836975098px] px-2 border-[0.5px] border-solid border-primary-main-blue"
                      >
                        <div
                          class="h-2 flex-1 relative text-5xs-1 tracking-[0.25px] leading-[7.1px] uppercase font-medium font-roboto text-primary-main-blue text-center flex items-center justify-center"
                        >
                          Anfragen
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div
                  class="self-stretch rounded-[4.06px] bg-base-white flex flex-col items-center justify-start p-[4.059319019317627px] box-border gap-[6.09px] max-w-full"
                >
                  <div
                    class="self-stretch overflow-hidden flex flex-row items-center justify-between py-0 pr-[6.0889787673950195px] pl-[9.133467674255371px] gap-[20px] shrink-0 mq750:flex-wrap"
                  >
                    <b
                      class="h-[26px] w-[318px] relative text-smi-2 tracking-[0.13px] leading-[110%] uppercase inline-block font-source-sans-pro text-primary-main-1 text-left"
                    >
                      <p class="m-0">
                        SachgeRECHT! Rechtliche Rahmenbedingungen für
                      </p>
                      <p class="m-0">Online-Trainings</p>
                    </b>
                    <div
                      class="w-[86.3px] flex flex-row items-center justify-start"
                    >
                      <div
                        class="flex flex-col items-start justify-start py-[3.0444893836975098px] pr-[3px] pl-[3.0444893836975098px]"
                      >
                        <img
                          class="w-[12.2px] h-[12.2px] relative"
                          alt=""
                          src="/wbs-arrow-7.svg"
                        />
                      </div>
                      <div
                        class="h-[13px] flex-1 relative text-4xs-1 leading-[12.18px] font-extrabold font-roboto text-secondary-dark-grey-900 text-left inline-block"
                      >
                        Nach Erstelldatum
                      </div>
                    </div>
                  </div>
                  <div
                    class="self-stretch flex flex-col items-center justify-start gap-[7.61px] max-w-full shrink-0"
                  >
                    <div
                      class="self-stretch rounded-[6.09px] flex flex-row flex-wrap items-start justify-center py-0 pr-[8.118638038635254px] pl-[4.059319019317627px] box-border [row-gap:20px] max-w-full"
                    >
                      <div
                        class="flex-1 flex flex-col items-center justify-start gap-[0.51px] min-w-[289px] max-w-full"
                      >
                        <div
                          class="self-stretch flex flex-col items-start justify-start"
                        >
                          <div
                            class="w-[294.8px] flex flex-row items-start justify-start"
                          >
                            <div
                              class="flex flex-col items-start justify-start py-[3.0444893836975098px] pr-[3px] pl-[3.0444893836975098px]"
                            >
                              <img
                                class="w-[12.2px] h-[12.2px] relative"
                                alt=""
                                src="/wbs-arrow-13.svg"
                              />
                            </div>
                            <div
                              class="h-[17px] w-[422.7px] flex flex-col items-start justify-center py-[3.0444893836975098px] px-0 box-border max-w-[143%] shrink-0"
                            >
                              <div
                                class="w-[45px] flex-1 relative text-5xs-1 leading-[10.66px] font-roboto text-secondary-dark-grey-900 text-left inline-block"
                              >
                                Gehirntraining
                              </div>
                            </div>
                          </div>
                        </div>
                        <div
                          class="self-stretch flex flex-row items-start justify-between py-0 px-[18px] box-border gap-[7.09px] max-w-full shrink-0 mq750:flex-wrap"
                        >
                          <div
                            class="h-[10.1px] w-[61.4px] relative text-5xs-1 tracking-[0.09px] leading-[140%] text-secondary-dark-grey-900 text-left inline-block shrink-0"
                          >
                            <b class="font-source-sans-pro">Trainer:in</b>
                            <span class="font-source-sans-pro"> </span>
                          </div>
                          <div
                            class="h-2.5 w-[339px] relative text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-secondary-dark-grey-900 text-left inline-block shrink-0 max-w-full"
                          >
                            Uwe van der Ploeg
                          </div>
                        </div>
                        <div
                          class="self-stretch flex flex-row items-start justify-between py-0 px-[18px] box-border gap-[20px] max-w-full shrink-0 mq750:flex-wrap"
                        >
                          <b
                            class="h-5 w-[47px] relative text-5xs-1 tracking-[0.09px] leading-[140%] inline-block font-source-sans-pro text-secondary-dark-grey-900 text-left"
                          >
                            <p class="m-0">Beschreibung:</p>
                          </b>
                          <div
                            class="h-10 w-[338px] relative text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-secondary-dark-grey-900 text-left inline-block shrink-0 max-w-full"
                          >
                            <p class="m-0">
                              Lebenslanges Lernen – ganz wunderbar. Aber was
                              tun, wenn das Lernen schwerfällt oder man sich
                              einfach
                            </p>
                            <p class="m-0">
                              nichts merken kann? Bei dem Train-the-Trainer
                              Seminar Gehirntraining oder Gedächtnistraining
                              werden wir u.a. die Themen Typgerecht lernen,
                              Lernmethoden und eine praktische Übung durchführen
                              anhand derer die eigene Merkfähigkeit getestet
                              werden kann.
                            </p>
                          </div>
                        </div>
                      </div>
                      <div
                        class="h-[19.1px] w-[29px] flex flex-col items-start justify-start py-[4.059319019317627px] px-0 box-border"
                      >
                        <div
                          class="self-stretch flex-1 flex flex-row items-start justify-end"
                        >
                          <b
                            class="self-stretch flex-1 relative text-5xs-1 leading-[10.66px] font-roboto text-primary-main-1 text-left"
                            >08.07.24</b
                          >
                        </div>
                      </div>
                    </div>
                    <div
                      class="self-stretch rounded-[6.09px] flex flex-row flex-wrap items-start justify-center py-0 pr-[8.118638038635254px] pl-[4.059319019317627px] box-border [row-gap:20px] max-w-full"
                    >
                      <div
                        class="flex-1 flex flex-row items-center justify-start min-w-[145px] max-w-full"
                      >
                        <div
                          class="w-[145.3px] flex flex-row items-center justify-start"
                        >
                          <div
                            class="flex flex-col items-start justify-start py-[3.0444893836975098px] pr-[3px] pl-[3.0444893836975098px]"
                          >
                            <img
                              class="w-[12.2px] h-[12.2px] relative"
                              alt=""
                              src="/wbs-arrow-7.svg"
                            />
                          </div>
                          <div
                            class="h-[11px] flex-1 relative text-5xs-1 leading-[10.66px] font-roboto text-secondary-dark-grey-900 text-left inline-block"
                          >
                            Die GTD-Methode (Getting Things Done)
                          </div>
                        </div>
                      </div>
                      <div
                        class="h-[19.1px] w-[29px] flex flex-col items-start justify-start py-[4.059319019317627px] px-0 box-border"
                      >
                        <div
                          class="self-stretch flex-1 flex flex-row items-start justify-end"
                        >
                          <b
                            class="self-stretch flex-1 relative text-5xs-1 leading-[10.66px] font-roboto text-primary-main-1 text-left"
                            >15.01.24</b
                          >
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="w-[126.9px] h-[57.8px] my-0 mx-[!important] absolute top-[28px] right-[20.8px] rounded-[2.03px] shadow-[2.5px_5.6px_6.09px_rgba(0,_0,_0,_0.3)] overflow-hidden shrink-0 flex flex-row items-start justify-start z-[1]"
              >
                <div
                  class="flex-1 rounded-[2.03px] bg-base-white flex flex-row items-center justify-center relative border-[0.5px] border-solid border-base-silver"
                >
                  <div
                    class="h-[48.2px] w-0.5 relative overflow-hidden shrink-0 hidden z-[0]"
                  />
                  <div
                    class="flex-1 rounded-[2.03px] flex flex-row items-center justify-center py-1 px-[3px]"
                  >
                    <div
                      class="flex-1 flex flex-row items-center justify-start gap-[1px]"
                    >
                      <div
                        class="overflow-hidden flex flex-row items-center justify-start py-0 pr-0.5 pl-[2.0296595096588135px]"
                      >
                        <img
                          class="h-[12.2px] w-[12.2px] relative object-cover"
                          alt=""
                          src="/wbs--success-24px@2x.png"
                        />
                      </div>
                      <div
                        class="flex-1 flex flex-col items-start justify-start pt-0 px-0 pb-0 gap-[1px]"
                      >
                        <div
                          class="self-stretch flex flex-row items-center justify-start py-0 pr-3 pl-0"
                        >
                          <div
                            class="flex-1 overflow-hidden flex flex-row items-center justify-center p-0.5"
                          >
                            <div
                              class="flex-1 relative text-5xs-1 leading-[10.66px] font-semibold font-source-sans-pro text-black text-left"
                            >
                              Dein Termin wurde erfolgreich gebucht
                            </div>
                          </div>
                          <div
                            class="h-[14.7px] w-[12.2px] relative overflow-hidden shrink-0 hidden"
                          />
                        </div>
                        <input
                          class="w-[calc(100%_-_0px)] [border:none] [outline:none] bg-[transparent] self-stretch h-[26px] overflow-hidden shrink-0 flex flex-row items-center justify-center pt-0 px-0.5 pb-px box-border font-source-sans-pro text-5xs-1 text-black min-w-[61px]"
                          placeholder="Du wirst in den nächsten Minuten eine Bestätigungsemail erhalten"
                          type="text"
                        />
                      </div>
                    </div>
                  </div>
                  <div
                    class="h-[48.2px] w-0.5 relative overflow-hidden shrink-0 hidden z-[2]"
                  />
                  <img
                    class="h-[14.7px] w-[12.2px] absolute my-0 mx-[!important] top-[4px] right-[3.9px] overflow-hidden shrink-0 z-[1]"
                    alt=""
                    src="/x.svg"
                  />
                </div>
                <div
                  class="h-full w-0.5 absolute my-0 mx-[!important] top-[0px] bottom-[0px] left-[0px] bg-success-main overflow-hidden shrink-0 z-[1]"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="w-[648px] h-[638px] shadow-[0px_0px_20px_rgba(0,_0,_0,_0.07)] overflow-hidden shrink-0 flex flex-row items-center justify-center pt-0 px-0 pb-px box-border max-w-full"
      >
        <div
          class="self-stretch flex-1 flex flex-col items-start justify-end py-0 pr-px pl-0 box-border max-w-full"
        >
          <div
            class="self-stretch h-[-525px] relative bg-base-white overflow-hidden shrink-0 max-w-full mq450:h-auto mq450:min-h-[-525]"
          >
            <div
              class="absolute top-[-0.7px] left-[130.3px] bg-whitesmoke-200 w-[518.2px] overflow-y-auto flex flex-col items-start justify-center max-w-full"
            >
              <div
                class="self-stretch bg-base-white flex flex-row items-start justify-end py-[2.5351414680480957px] px-[9.126508712768555px]"
              >
                <div
                  class="w-[97.4px] overflow-hidden shrink-0 flex flex-row items-center justify-start py-[6.084339141845703px] pr-1 pl-[4.0562262535095215px] box-border gap-[12.17px]"
                >
                  <img
                    class="h-[12.2px] w-[12.2px] relative overflow-hidden shrink-0 min-h-[12px]"
                    alt=""
                    src="/filledactionaccountcircle-1.svg"
                  />
                  <div
                    class="h-[11px] flex-1 relative text-4xs-1 leading-[10.65px] font-medium font-roboto text-primary-saturated text-left inline-block shrink-0"
                  >
                    Maximilian Müller
                  </div>
                </div>
              </div>
              <div
                class="self-stretch h-[736.2px] overflow-y-auto shrink-0 flex flex-col items-center justify-start p-[12.168678283691406px] box-border gap-[12.17px] max-w-full mq450:h-auto"
              >
                <div
                  class="self-stretch rounded-[4.06px] bg-base-white flex flex-col items-start justify-start p-[6.084339141845703px] box-border max-w-full shrink-0"
                >
                  <b
                    class="w-[415px] h-[13px] relative text-smi-2 tracking-[0.13px] leading-[110%] uppercase inline-block font-source-sans-pro text-primary-main-1 text-left max-w-full"
                    >Das Bildungsverständnis als Unterstützung im WBS Campus
                    Alltag</b
                  >
                </div>
                <div
                  class="self-stretch rounded-[4.06px] bg-base-white flex flex-col items-start justify-start p-[6.084339141845703px] shrink-0 whitespace-nowrap"
                >
                  <div
                    class="self-stretch h-[130px] relative text-5xs-1 leading-[140%] text-primary-main-1 text-left inline-block"
                  >
                    <p class="m-0">
                      <b class="tracking-[0.05px] font-source-sans-pro"
                        >Beschreibung:</b
                      >
                    </p>
                    <p class="m-0 tracking-[0.09px] font-source-sans-pro">
                      Wir kennen das WBS Bildungsverständnis, doch wenden wir es
                      auch in unserer täglichen Arbeit an? Wie kann uns die
                      Nutzung des Wissens im Alltag mit den Teilnehmenden
                      dienen? Was macht die regelmäßige Anwendung des
                      H-A-K-E-Prinzips für einen Unterschied?Unter Beachtung der
                      ganzheitlichen Förderung von Fach- und Methodenkompetenz,
                      Sozial- und Kommunikationskompetenz, personaler Kompetenz
                      sowie der Umsetzungs- und Aktivitätskompetenz bei der WBS,
                      unterstützt dieses Train-the-Trainer-Seminar den Aufbau
                      des Miteinanders im digitalen Raum durch Kursleitung oder
                      Lernbegleitende, sowie das Aufstellen von wertebasierten
                      Leitplanken, um allen Beteiligten Sicherheit, Struktur und
                      Orientierung zu geben.Themenübersicht:Lerne in diesem
                      Austauschformat, wie du:
                    </p>
                    <ul class="m-0 font-source-sans-pro text-inherit pl-[9px]">
                      <li class="mb-0">
                        <span class="tracking-[0.09px] font-source-sans-pro"
                          >die Interaktion klärst und stärkst,</span
                        >
                      </li>
                      <li class="mb-0">
                        <span class="tracking-[0.09px] font-source-sans-pro"
                          >einen sicheren Raum für Wachstum schaffst,</span
                        >
                      </li>
                      <li class="mb-0">
                        <span class="tracking-[0.09px] font-source-sans-pro"
                          >Handlungssicherheit in Konfliktsituationen durch
                          Vereinbarungen erhälst,</span
                        >
                      </li>
                      <li class="mb-0">
                        <span class="tracking-[0.09px] font-source-sans-pro"
                          >die Eigenverantwortung der Teilnehmenden trotz oder
                          mit Inhaltsdichte im Unterrichtsgeschehen
                          förderst.</span
                        >
                      </li>
                    </ul>
                    <p class="m-0 tracking-[0.09px] font-source-sans-pro">
                      Als Vorbereitung für diesen Kurs empfehlen wir das erneute
                      Anschauen des Selbstlernmoduls „Das Bildungsverständnis in
                      der WBS Gruppe – Umsetzung in der Praxis“
                    </p>
                  </div>
                </div>
                <Experience /><Experience /><Experience /><Experience /><Experience />
              </div>
            </div>
            <div
              class="absolute top-[-52.7px] left-[0px] w-full flex flex-row items-end justify-start pt-[52px] px-0 pb-[162px] box-border gap-[78px] mq450:gap-[39px]"
            >
              <div
                class="w-[130.8px] bg-base-white shadow-[0px_1.5px_7.1px_1.01px_rgba(0,_0,_0,_0.12),_0px_4.1px_5.07px_0.51px_rgba(0,_0,_0,_0.14),_0px_2.5px_2.54px_-1.52px_rgba(0,_0,_0,_0.2)] overflow-hidden shrink-0 flex flex-col items-start justify-start pt-[17px] px-0 pb-0 box-border gap-[248px]"
              >
                <div
                  class="self-stretch flex flex-col items-end justify-start pt-[50px] px-0 pb-0 relative gap-[29px]"
                >
                  <img
                    class="w-[28.9px] h-[30.4px] absolute my-0 mx-[!important] top-[0.1px] right-[52.1px]"
                    alt=""
                    src="/wbs-logo-2.svg"
                  />
                  <div
                    class="self-stretch h-[17px] flex flex-col items-center justify-start gap-[4px]"
                  >
                    <b
                      class="w-[53px] h-[13px] relative text-smi-2 tracking-[0.13px] leading-[110%] inline-block font-source-sans-pro text-secondary-dark-grey-900 text-center"
                    >
                      <span class="uppercase">T</span>
                      <span class="capitalize">rainspot</span>
                    </b>
                    <div
                      class="self-stretch h-[0.51px] relative box-border border-t-[0.5px] border-solid border-base-silver"
                    />
                  </div>
                  <frame
                    wBSDASH="/wbsdash-2.svg"
                    icon2="/icon-2-6.svg"
                    wBSList24px="/wbs--list-24px-1.svg"
                    propFlex="unset"
                    propWidth="unset"
                    propAlignSelf="stretch"
                  />
                </div>
                <div
                  class="w-0.5 h-[18.3px] relative rounded-[12.68px] bg-primary-main-1 hidden"
                />
                <div
                  class="w-[122.2px] h-4 hidden flex-row items-start justify-start gap-[8.11px]"
                >
                  <img
                    class="h-[13.2px] w-[13.2px] relative"
                    alt=""
                    src="/icon-2-7.svg"
                  />
                  <b
                    class="self-stretch flex-1 relative text-3xs-1 tracking-[-0.02em] leading-[15.21px] font-dm-sans text-base-silver text-left shrink-0"
                    >Assessments</b
                  >
                  <div
                    class="h-[18.3px] w-0.5 relative rounded-[12.68px] bg-primary-main-1 hidden"
                  />
                </div>
                <div
                  class="w-[122.2px] h-4 hidden flex-row items-start justify-start gap-[8.11px]"
                >
                  <img
                    class="h-[13.2px] w-[13.2px] relative"
                    alt=""
                    src="/icon-2-8.svg"
                  />
                  <b
                    class="self-stretch flex-1 relative text-3xs-1 tracking-[-0.02em] leading-[15.21px] font-dm-sans text-base-silver text-left shrink-0"
                    >Bildungsreise</b
                  >
                  <div
                    class="h-[18.3px] w-0.5 relative rounded-[12.68px] bg-primary-main-1 hidden"
                  />
                </div>
                <NavFooter logosWBSMedium="/logos--wbs--medium-2.svg" />
              </div>
              <div
                class="h-full w-full absolute my-0 mx-[!important] top-[-0.1px] right-[0.5px] bottom-[0.2px] left-[-0.5px] bg-gray z-[4]"
              />
              <div
                class="h-[293px] w-[236px] flex flex-col items-start justify-start mq450:h-auto"
              >
                <div
                  class="self-stretch h-[234px] flex flex-row items-center justify-center relative mq450:h-auto"
                >
                  <div
                    class="h-[93.3px] w-[518.2px] my-0 mx-[!important] absolute right-[-204.5px] bottom-[-59.9px] bg-base-white overflow-hidden shrink-0 flex flex-col items-center justify-start pt-0 px-0 pb-2.5 box-border gap-[10px] z-[1] mq450:h-auto"
                  >
                    <div
                      class="self-stretch h-[0.51px] relative box-border border-t-[0.5px] border-solid border-base-silver"
                    />
                    <div
                      class="self-stretch flex flex-row items-start justify-start py-0 pr-[27px] pl-[19px] box-border max-w-full"
                    >
                      <div
                        class="flex-1 flex flex-row items-center justify-between gap-[20px] max-w-full mq450:flex-wrap"
                      >
                        <div
                          class="h-[57px] w-[249px] flex flex-col items-start justify-start gap-[17px]"
                        >
                          <div
                            class="w-[125.6px] flex-1 relative text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-primary-main-1 whitespace-pre-wrap text-left inline-block"
                          >
                            <p class="m-0">
                              Seminargebühr: 25,00 € zzgl. MwSt.
                            </p>
                          </div>
                          <div
                            class="self-stretch flex-1 relative text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-black text-left"
                          >
                            Terminbuchungen sind bis 24h vor Seminarbeginn
                            möglichKostenfreie Stornierung bis 10 Tage vor
                            Seminarbeginn
                          </div>
                        </div>
                        <div
                          class="w-12 flex flex-col items-start justify-start py-0 pr-px pl-0 box-border gap-[9px]"
                        >
                          <div
                            class="self-stretch rounded-[2.03px] flex flex-row items-center justify-center py-[5px] pr-[7px] pl-2 border-[0.5px] border-solid border-primary-main-blue"
                          >
                            <div
                              class="h-2 w-[30px] relative text-5xs-1 tracking-[0.25px] leading-[7.1px] uppercase font-medium font-roboto text-primary-main-blue text-center flex items-center justify-center"
                            >
                              Buchen
                            </div>
                          </div>
                          <div
                            class="self-stretch rounded-[2.03px] flex flex-row items-center justify-center py-[5px] pr-[7px] pl-2 border-[0.5px] border-solid border-primary-main-blue"
                          >
                            <div
                              class="h-2 w-[30px] relative text-5xs-1 tracking-[0.25px] leading-[7.1px] uppercase font-medium font-roboto text-primary-main-blue text-center flex items-center justify-center"
                            >
                              Buchen
                            </div>
                          </div>
                          <div
                            class="self-stretch rounded-[2.03px] flex flex-row items-center justify-center py-[5px] pr-[7px] pl-2 border-[0.5px] border-solid border-primary-main-blue"
                          >
                            <div
                              class="h-2 w-[30px] relative text-5xs-1 tracking-[0.25px] leading-[7.1px] uppercase font-medium font-roboto text-primary-main-blue text-center flex items-center justify-center"
                            >
                              Buchen
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div
                      class="w-[126px] h-[30px] flex flex-row items-start justify-start relative"
                    >
                      <div
                        class="self-stretch w-full absolute my-0 mx-[!important] top-[-86.3px] left-[143.8px] text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-primary-main-1 text-left inline-block h-full z-[1]"
                      >
                        <p class="m-0">01.02.2024-</p>
                        <p class="m-0">Lamprecht, Monika</p>
                      </div>
                      <div
                        class="self-stretch flex-1 relative text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-primary-main-1 text-left z-[2]"
                      >
                        <p class="m-0">01.04.2024</p>
                        <p class="m-0">Lamprecht, Monika</p>
                      </div>
                      <div
                        class="self-stretch w-full absolute my-0 mx-[!important] bottom-[29.6px] left-[143.8px] text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-primary-main-1 text-left inline-block h-full z-[3]"
                      >
                        <p class="m-0">01.05.2024</p>
                        <p class="m-0">Lamprecht, Monika</p>
                      </div>
                    </div>
                  </div>
                  <div
                    class="self-stretch flex-1 rounded-[2.03px] bg-base-white shadow-[0px_2px_7.61px_rgba(94,_122,_160,_0.18),_0px_2px_25.35px_rgba(94,_122,_160,_0.18)] overflow-hidden flex flex-col items-start justify-start z-[5]"
                  >
                    <div
                      class="self-stretch h-[21px] flex flex-col items-start justify-start py-[4.0562262535095215px] px-[8.112452507019043px] box-border"
                    >
                      <div
                        class="w-[148px] flex-1 overflow-hidden flex flex-row items-start justify-start gap-[12.17px]"
                      >
                        <b
                          class="self-stretch flex-1 relative text-smi-2 tracking-[0.13px] leading-[110%] uppercase flex font-source-sans-pro text-primary-main-1 text-left items-end"
                          >Buchungsbestätingung</b
                        >
                        <div
                          class="rounded-[2.03px] hidden flex-row items-center justify-start border-[0.5px] border-solid border-primary-main-1"
                        >
                          <div
                            class="flex flex-row items-center justify-start py-[4.0562262535095215px] pr-1 pl-[4.0562262535095215px]"
                          >
                            <div class="h-[12.2px] w-[12.2px] relative">
                              <img
                                class="relative w-[10.1px] h-[10.1px]"
                                alt=""
                                src="/icon-color.svg"
                              />
                              <div
                                class="absolute top-[0px] left-[7.1px] rounded-[50%] bg-base-white box-border w-[5.1px] h-[5.1px] border-[0.5px] border-solid border-primary-main-1"
                              />
                              <b
                                class="absolute top-[1px] left-[8.6px] text-[4.1px] leading-[2.03px] flex font-source-sans-pro text-primary-main-1 text-left items-center w-[2.5px] h-[2.5px]"
                                >x</b
                              >
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div
                      class="self-stretch flex-1 flex flex-col items-start justify-start p-[12.168678283691406px]"
                    >
                      <b
                        class="self-stretch h-[22px] relative text-5xs-1 leading-[10.65px] inline-block font-roboto text-secondary-dark-grey-900 text-left"
                        >Selbst ist der Lernende – Gestaltung und Organisation
                        von Selbstlernprozessen</b
                      >
                      <div
                        class="self-stretch h-[30px] relative text-5xs-1 tracking-[0.09px] leading-[140%] text-primary-main-1 whitespace-pre-wrap text-left inline-block"
                      >
                        <p class="m-0 font-source-sans-pro">&nbsp;</p>
                        <p class="m-0">
                          <span class="font-source-sans-pro"
                            >Seminargebühr
                          </span>
                          <b class="font-source-sans-pro">25,00 € </b>
                          <span class="font-source-sans-pro">zzgl. MwSt.</span>
                        </p>
                      </div>
                      <div
                        class="self-stretch h-5 relative text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-primary-main-1 text-left inline-block"
                      >
                        <p class="m-0">01.02.2024</p>
                      </div>
                      <div
                        class="self-stretch flex-1 flex flex-col items-start justify-start gap-[12.17px]"
                      >
                        <div
                          class="self-stretch flex-1 relative text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-primary-main-1 text-left"
                        >
                          Terminbuchungen sind bis 24h vor Seminarbeginn
                          möglichKostenfreie Stornierung bis 10 Tage vor
                          Seminarbeginn
                        </div>
                        <div
                          class="self-stretch flex-1 overflow-hidden flex flex-row items-start justify-start gap-[4.06px]"
                        >
                          <img
                            class="h-[12.2px] w-[12.2px] relative object-cover"
                            alt=""
                            src="/wbs-checkbox--unselected@2x.png"
                          />
                          <div
                            class="self-stretch flex-1 flex flex-row items-start justify-start"
                          >
                            <div
                              class="self-stretch flex-1 relative text-5xs-1 leading-[10.65px] font-source-sans-pro text-primary-main-1 text-left"
                            >
                              Ich akzeptiere die
                              <span class="[text-decoration:underline]"
                                >Allgemeinen Geschäftsbedingungen der WBS
                                TRAINING AG</span
                              >
                            </div>
                          </div>
                        </div>
                      </div>
                      <div
                        class="self-stretch h-5 relative text-5xs-1 tracking-[0.09px] leading-[140%] font-source-sans-pro text-primary-main-1 text-left inline-block"
                      >
                        <p class="m-0">&nbsp;</p>
                      </div>
                    </div>
                    <div
                      class="self-stretch h-[18px] flex flex-row items-start justify-between py-0 px-[7.098395824432373px] box-border gap-[20px]"
                    >
                      <div
                        class="self-stretch w-[59px] rounded-[2.03px] box-border flex flex-row items-center justify-center py-[3.0421695709228516px] px-2 border-[0.5px] border-solid border-primary-main-blue"
                      >
                        <div
                          class="h-2 flex-1 relative text-5xs-1 tracking-[0.25px] leading-[7.1px] uppercase font-medium font-roboto text-primary-main-blue text-center flex items-center justify-center"
                        >
                          Abbrechen
                        </div>
                      </div>
                      <div
                        class="self-stretch w-[46px] rounded-[2.03px] box-border flex flex-row items-center justify-center py-[3.0421695709228516px] px-2 border-[0.5px] border-solid border-action-states-light-mode-disabled"
                      >
                        <div
                          class="h-2 flex-1 relative text-5xs-1 tracking-[0.25px] leading-[7.1px] uppercase font-medium font-roboto text-text-color-light-mode-disabled text-center flex items-center justify-center"
                        >
                          Buchen
                        </div>
                      </div>
                    </div>
                    <div
                      class="self-stretch h-6 flex flex-col items-start justify-start py-[4.0562262535095215px] px-[8.112452507019043px] box-border"
                    >
                      <div
                        class="w-[172px] overflow-hidden hidden flex-row items-center justify-start gap-[12.17px]"
                      >
                        <div class="h-[20.3px] w-[69px] relative">
                          <div
                            class="absolute top-[0px] left-[calc(50%_-_10.2px)] rounded-[2.03px] w-[20.3px] h-[20.3px]"
                          >
                            <img
                              class="absolute w-full top-[0px] right-[0px] left-[0px] max-w-full overflow-hidden h-full"
                              alt=""
                              src="/base.svg"
                            />
                            <div
                              class="absolute top-[calc(50%_-_5.05px)] left-[26.6%] text-5xs-1 leading-[10.14px] font-source-sans-pro text-base-black text-center"
                            >
                              10
                            </div>
                          </div>
                          <div
                            class="absolute top-[0px] left-[calc(50%_-_34.5px)] rounded-[2.03px] w-[20.3px] h-[20.3px]"
                          >
                            <img
                              class="absolute w-full top-[0px] right-[0px] left-[0px] max-w-full overflow-hidden h-full"
                              alt=""
                              src="/base.svg"
                            />
                            <div
                              class="absolute top-[calc(50%_-_5.05px)] left-[36.45%] text-5xs-1 leading-[10.14px] font-source-sans-pro text-base-black text-center"
                            >
                              5
                            </div>
                          </div>
                          <div
                            class="absolute top-[0px] left-[calc(50%_+_14.2px)] rounded-[2.03px] w-[20.3px] h-[20.3px]"
                          >
                            <img
                              class="absolute w-full top-[0px] right-[0px] left-[0px] max-w-full overflow-hidden h-full"
                              alt=""
                              src="/base.svg"
                            />
                            <div
                              class="absolute top-[calc(50%_-_5.05px)] left-[23.65%] text-5xs-1 leading-[10.14px] font-source-sans-pro text-base-black text-center"
                            >
                              100
                            </div>
                            <div
                              class="absolute w-full top-[0px] right-[0%] left-[0%] h-full"
                            >
                              <img
                                class="absolute w-full top-[0px] right-[0px] left-[0px] max-w-full overflow-hidden h-full"
                                alt=""
                                src="/base-3.svg"
                              />
                              <div
                                class="absolute top-[calc(50%_-_5.05px)] left-[26.11%] text-5xs-1 leading-[10.14px] font-source-sans-pro text-base-white text-center"
                              >
                                25
                              </div>
                            </div>
                          </div>
                        </div>
                        <div
                          class="h-[15px] flex-1 overflow-hidden flex flex-row items-center justify-start py-[2.0281131267547607px] pr-1 pl-[4.0562262535095215px] box-border"
                        >
                          <div
                            class="self-stretch flex-1 relative text-5xs-1 leading-[10.65px] text-base-black text-left"
                          >
                            <span class="font-semibold font-source-sans-pro"
                              >show 1 to 25</span
                            >
                            <span class="font-source-sans-pro">
                              of 1014 entries</span
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="w-[648px] h-[638px] shadow-[0px_0px_20px_rgba(0,_0,_0,_0.07)] overflow-hidden shrink-0 flex flex-row items-center justify-center max-w-full"
      >
        <div
          class="self-stretch flex-1 bg-base-white overflow-hidden flex flex-row items-start justify-start max-w-full"
        >
          <div
            class="self-stretch w-[129px] bg-base-white shadow-[0px_1.5px_7.01px_1px_rgba(0,_0,_0,_0.12),_0px_4px_5.01px_0.5px_rgba(0,_0,_0,_0.14),_0px_2.5px_2.5px_-1.5px_rgba(0,_0,_0,_0.2)] overflow-hidden shrink-0 flex flex-col items-end justify-start pt-4 px-0 pb-0 box-border gap-[28px] mq450:hidden"
          >
            <div
              class="self-stretch flex flex-col items-center justify-start gap-[20px]"
            >
              <img
                class="w-[28.5px] h-[30px] relative"
                alt=""
                src="/wbs-logo-3.svg"
              />
              <div
                class="self-stretch h-[17px] flex flex-col items-center justify-start gap-[4px]"
              >
                <h2
                  class="m-0 w-[52px] h-[13px] relative text-xs tracking-[0.13px] leading-[110%] font-bold font-source-sans-pro text-secondary-dark-grey-900 text-center inline-block"
                >
                  <span class="uppercase">T</span>
                  <span class="capitalize">rainspot</span>
                </h2>
                <div
                  class="self-stretch h-[0.5px] relative box-border border-t-[0.5px] border-solid border-base-silver"
                />
              </div>
            </div>
            <div
              class="w-0.5 h-[18px] relative rounded-[12.52px] bg-primary-main-1 hidden"
            />
            <div
              class="w-[116px] flex-1 flex flex-col items-start justify-start gap-[8px]"
            >
              <div
                class="self-stretch flex flex-row items-center justify-start gap-[9px]"
              >
                <img
                  class="h-3 w-3 relative overflow-hidden shrink-0"
                  alt=""
                  src="/wbsdash-3.svg"
                />
                <div
                  class="flex-1 flex flex-row items-center justify-start gap-[8px]"
                >
                  <b
                    class="h-[11px] flex-1 relative text-5xs tracking-[0.08px] leading-[140%] inline-block font-source-sans-pro text-secondary-dark-grey-900 text-left"
                    >Allgemein</b
                  >
                  <div
                    class="h-[18px] w-0.5 relative rounded-[12.52px] bg-primary-main-1"
                  />
                </div>
              </div>
              <div
                class="self-stretch flex flex-row items-center justify-start gap-[9px]"
              >
                <img
                  class="h-[13px] w-[13px] relative min-h-[13px]"
                  alt=""
                  src="/icon-2-9.svg"
                />
                <div
                  class="h-[11px] flex-1 relative text-5xs tracking-[0.08px] leading-[140%] font-source-sans-pro text-base-silver text-left inline-block"
                >
                  Meine Seminare
                </div>
              </div>
              <div
                class="self-stretch flex flex-row items-start justify-start gap-[9px]"
              >
                <img
                  class="h-3 w-3 relative min-h-[12px]"
                  alt=""
                  src="/wbs--list-24px-2.svg"
                />
                <div
                  class="h-[11px] flex-1 relative text-5xs tracking-[0.08px] leading-[140%] font-source-sans-pro text-base-silver text-left inline-block"
                >
                  Seminarprogramm
                </div>
              </div>
            </div>
            <div
              class="w-0.5 h-[18px] relative rounded-[12.52px] bg-primary-main-1 hidden"
            />
            <div
              class="w-[120.7px] h-4 hidden flex-row items-start justify-start gap-[8.01px]"
            >
              <img
                class="h-[13px] w-[13px] relative"
                alt=""
                src="/icon-2-10.svg"
              />
              <b
                class="self-stretch flex-1 relative text-4xs tracking-[-0.02em] leading-[15.02px] font-dm-sans text-base-silver text-left shrink-0"
                >Assessments</b
              >
              <div
                class="h-[18px] w-0.5 relative rounded-[12.52px] bg-primary-main-1 hidden"
              />
            </div>
            <div
              class="w-[120.7px] h-4 hidden flex-row items-start justify-start gap-[8.01px]"
            >
              <img
                class="h-[13px] w-[13px] relative"
                alt=""
                src="/icon-2-11.svg"
              />
              <b
                class="self-stretch flex-1 relative text-4xs tracking-[-0.02em] leading-[15.02px] font-dm-sans text-base-silver text-left shrink-0"
                >Bildungsreise</b
              >
              <div
                class="h-[18px] w-0.5 relative rounded-[12.52px] bg-primary-main-1 hidden"
              />
            </div>
            <div
              class="self-stretch bg-base-white overflow-hidden flex flex-row items-end justify-center pt-8 px-4 pb-4"
            >
              <div
                class="flex-1 overflow-hidden flex flex-col items-center justify-start py-0 px-[17px] gap-[7px]"
              >
                <img
                  class="w-[45.1px] h-[15.5px] relative overflow-hidden shrink-0"
                  alt=""
                  src="/logos--wbs--medium-3.svg"
                />
                <div
                  class="self-stretch h-1.5 relative text-[5.1px] font-roboto text-darkslateblue text-center inline-block"
                >
                  © 2022 WBS TRAINING AG
                </div>
              </div>
            </div>
          </div>
          <div
            class="h-[638px] flex-1 flex flex-col items-start justify-start pt-0 px-0 pb-0 box-border max-w-[calc(100%_-_129px)] mq450:h-auto mq450:max-w-full"
          >
            <div
              class="self-stretch h-[756px] relative max-w-full mq450:h-auto mq450:min-h-[756]"
            >
              <div
                class="absolute top-[0.3px] left-[0px] bg-whitesmoke-200 w-full overflow-y-auto flex flex-col items-start justify-center h-full max-w-full"
              >
                <div
                  class="self-stretch bg-base-white flex flex-row items-start justify-end py-[2.50411057472229px] px-[9.014798164367676px]"
                >
                  <div
                    class="w-[96.1px] overflow-hidden shrink-0 flex flex-row items-center justify-start py-[6.009865760803223px] pr-1 pl-[4.006577014923096px] box-border gap-[12.02px]"
                  >
                    <img
                      class="h-3 w-3 relative overflow-hidden shrink-0 min-h-[12px]"
                      alt=""
                      src="/filledactionaccountcircle-2.svg"
                    />
                    <div
                      class="h-[11px] flex-1 relative text-5xs leading-[10.52px] font-medium font-roboto text-primary-saturated text-left inline-block"
                    >
                      Maximilian Müller
                    </div>
                  </div>
                </div>
                <div
                  class="self-stretch h-[727px] overflow-y-auto shrink-0 flex flex-col items-center justify-start p-[12.019731521606445px] box-border gap-[12.02px] max-w-full mq450:h-auto"
                >
                  <div
                    class="self-stretch rounded-[4.01px] bg-base-white flex flex-col items-start justify-start p-[6.009865760803223px] box-border gap-[6.01px] max-w-full shrink-0"
                  >
                    <h2
                      class="m-0 w-[410px] h-[13px] relative text-xs tracking-[0.13px] leading-[110%] uppercase font-bold font-source-sans-pro text-primary-main-1 text-left inline-block max-w-full"
                    >
                      Das Bildungsverständnis als Unterstützung im WBS Campus
                      Alltag
                    </h2>
                    <div
                      class="self-stretch h-[180px] relative text-6xs leading-[140%] text-primary-main-1 text-left inline-block"
                    >
                      <p class="m-0">
                        <b class="tracking-[0.05px] font-source-sans-pro"
                          >&nbsp;</b
                        >
                      </p>
                      <p class="m-0">
                        <span class="tracking-[0.09px]">
                          <span class="font-source-sans-pro"
                            >Wir kennen das WBS Bildungsverständnis, doch wenden
                            wir es auch in unserer täglichen Arbeit an? Wie kann
                            uns die Nutzung des Wissens im Alltag mit den
                            Teilnehmenden dienen? Was macht die regelmäßige
                            Anwendung des H-A-K-E-Prinzips für einen
                            Unterschied?Unter Beachtung der ganzheitlichen
                            Förderung von Fach- und Methodenkompetenz, Sozial-
                            und Kommunikationskompetenz, personaler Kompetenz
                            sowie der Umsetzungs- und Aktivitätskompetenz bei
                            der WBS, unterstützt dieses
                            Train-the-Trainer-Seminar den Aufbau des
                            Miteinanders im digitalen Raum durch Kursleitung
                            oder Lernbegleitende, sowie das Aufstellen von
                            wertebasierten Leitplanken, um allen Beteiligten
                            Sicherheit, Struktur und Orientierung zu geben.  Als
                            Vorbereitung für diesen Kurs empfehlen wir das
                            erneute Anschauen des Selbstlernmoduls „Das
                            Bildungsverständnis in der WBS Gruppe – Umsetzung in
                            der Praxis“  </span
                          >
                          <b class="font-source-sans-pro">Themenübersicht:</b>
                        </span>
                      </p>
                      <ul
                        class="m-0 font-source-sans-pro text-inherit pl-[9px]"
                      >
                        <li class="mb-0">
                          <span class="tracking-[0.09px]">
                            <span class="font-source-sans-pro"
                              >Lerne in diesem Austauschformat, wie du:</span
                            >
                          </span>
                        </li>
                        <li class="mb-0">
                          <span class="tracking-[0.09px]">
                            <span class="font-source-sans-pro"
                              >die Interaktion klärst und stärkst,</span
                            >
                          </span>
                        </li>
                        <li class="mb-0">
                          <span class="tracking-[0.09px]">
                            <span class="font-source-sans-pro"
                              >einen sicheren Raum für Wachstum schaffst,</span
                            >
                          </span>
                        </li>
                        <li class="mb-0">
                          <span class="tracking-[0.09px]">
                            <span class="font-source-sans-pro"
                              >Handlungssicherheit in Konfliktsituationen durch
                              Vereinbarungen erhälst,</span
                            >
                          </span>
                        </li>
                        <li class="mb-0">
                          <span class="tracking-[0.09px]">
                            <span class="font-source-sans-pro"
                              >die Eigenverantwortung der Teilnehmenden trotz
                              oder mit Inhaltsdichte im Unterrichtsgeschehen
                              förderst. </span
                            >
                          </span>
                        </li>
                      </ul>
                    </div>
                  </div>
                  <div
                    class="self-stretch flex flex-row flex-wrap items-start justify-center gap-[12.02px]"
                  >
                    <div
                      class="flex-1 rounded-[4.01px] bg-base-white flex flex-col items-start justify-start p-[6.009865760803223px] box-border min-w-[157px] whitespace-nowrap"
                    >
                      <div
                        class="self-stretch h-[100px] relative text-6xs leading-[140%] text-primary-main-1 text-left inline-block"
                      >
                        <p class="m-0">
                          <b class="tracking-[0.05px] font-source-sans-pro"
                            >Kompetenzorientierung:</b
                          >
                        </p>
                        <ul
                          class="m-0 font-source-sans-pro text-inherit pl-[9px]"
                        >
                          <li class="mb-0">
                            <span class="tracking-[0.09px]">
                              <span class="font-source-sans-pro"
                                >Beziehungsmanagement</span
                              >
                            </span>
                          </li>
                          <li class="mb-0">
                            <span class="tracking-[0.09px]">
                              <span class="font-source-sans-pro"
                                >Kommunikationsfähigkeit</span
                              >
                            </span>
                          </li>
                          <li class="mb-0">
                            <span class="tracking-[0.09px]">
                              <span class="font-source-sans-pro"
                                >Lern- und Veränderungsbereitschaft</span
                              >
                            </span>
                          </li>
                          <li class="mb-0">
                            <span class="tracking-[0.09px]">
                              <span class="font-source-sans-pro"
                                >Teamfähigkeit</span
                              >
                            </span>
                          </li>
                          <li class="mb-0">
                            <span class="tracking-[0.09px]">
                              <span class="font-source-sans-pro"
                                >Zielorientierung</span
                              >
                              <b class="font-source-sans-pro">&nbsp;</b>
                            </span>
                          </li>
                        </ul>
                        <p class="m-0">
                          <b class="font-source-sans-pro">
                            <span class="tracking-[0.05px]">Methoden:</span>
                          </b>
                        </p>
                        <ul
                          class="m-0 font-source-sans-pro text-inherit pl-[9px]"
                        >
                          <li class="mb-0">
                            <span class="tracking-[0.09px] font-source-sans-pro"
                              >Input</span
                            >
                          </li>
                          <li>
                            <span class="tracking-[0.09px] font-source-sans-pro"
                              >Austausch</span
                            >
                          </li>
                        </ul>
                      </div>
                    </div>
                    <div
                      class="flex-1 rounded-[4.01px] bg-base-white flex flex-col items-start justify-start p-[6.009865760803223px] box-border min-w-[157px] whitespace-nowrap"
                    >
                      <div
                        class="self-stretch h-[60px] relative text-6xs leading-[140%] text-left inline-block"
                      >
                        <p class="m-0">
                          <span class="text-primary-main-1">
                            <b class="tracking-[0.05px] font-source-sans-pro"
                              >Maximale Anzahl der Teilnehmer:</b
                            >
                          </span>
                        </p>
                        <p class="m-0">
                          <span class="text-primary-main-1">
                            <span class="tracking-[0.09px] font-source-sans-pro"
                              >15</span
                            >
                          </span>
                        </p>
                        <p class="m-0">
                          <span class="text-primary-main-1">
                            <b class="tracking-[0.05px] font-source-sans-pro"
                              >Teilnahmebescheinigung:</b
                            >
                          </span>
                        </p>
                        <p class="m-0">
                          <span class="text-primary-main-1">
                            <span class="tracking-[0.09px] font-source-sans-pro"
                              >Du erhältst eine Teilnahmebescheinigung.</span
                            >
                          </span>
                        </p>
                        <p class="m-0">
                          <span class="tracking-[0.09px] font-source-sans-pro">
                            <span class="text-firebrick">&nbsp;</span>
                          </span>
                        </p>
                      </div>
                    </div>
                  </div>
                  <NavLine propHeight="86.1px" /><NavLine
                    propHeight="100px"
                  /><NavLine propHeight="100px" /><NavLine propHeight="100px" />
                </div>
              </div>
              <div
                class="absolute top-[481.3px] left-[0px] bg-base-white w-full overflow-hidden flex flex-col items-center justify-start pt-0 px-0 pb-[53px] box-border gap-[8px] max-w-full z-[1]"
              >
                <div
                  class="self-stretch h-[0.5px] relative box-border border-t-[0.5px] border-solid border-base-silver"
                />
                <div
                  class="self-stretch flex flex-row items-start justify-start py-0 pr-[27px] pl-[19px] box-border max-w-full shrink-0"
                >
                  <div
                    class="flex-1 flex flex-row flex-wrap items-start justify-start gap-[70px] max-w-full mq750:gap-[35px]"
                  >
                    <div
                      class="flex-1 flex flex-col items-start justify-start pt-2 px-0 pb-0 box-border min-w-[160px]"
                    >
                      <div
                        class="self-stretch h-[57px] flex flex-col items-start justify-start gap-[17px]"
                      >
                        <div
                          class="w-[124px] flex-1 relative text-6xs tracking-[0.09px] leading-[140%] text-primary-main-1 whitespace-pre-wrap text-left inline-block"
                        >
                          <p class="m-0">
                            <span class="font-source-sans-pro"
                              >Seminargebühr:
                            </span>
                            <b class="font-source-sans-pro">25,00 € </b>
                            <span class="font-source-sans-pro"
                              >zzgl. MwSt.</span
                            >
                          </p>
                        </div>
                        <div
                          class="self-stretch flex-1 relative text-6xs tracking-[0.09px] leading-[140%] font-source-sans-pro text-primary-main-1 text-left"
                        >
                          Terminbuchungen sind bis 24h vor Seminarbeginn
                          möglichKostenfreie Stornierung bis 10 Tage vor
                          Seminarbeginn
                        </div>
                      </div>
                    </div>
                    <div
                      class="h-24 w-[150px] flex flex-row items-start justify-between gap-[20px]"
                    >
                      <div
                        class="self-stretch w-[67px] flex flex-col items-start justify-start gap-[26px]"
                      >
                        <div
                          class="self-stretch h-[30px] flex flex-row items-start justify-start relative"
                        >
                          <div
                            class="self-stretch flex-1 relative text-6xs tracking-[0.09px] leading-[140%] text-primary-main-1 text-left cursor-pointer"
                            @click="onDetaillierteInfosTextClick"
                          >
                            <p class="m-0 font-source-sans-pro">25.03.2024</p>
                            <p class="m-0">
                              <b
                                class="[text-decoration:underline] font-source-sans-pro"
                                >Detaillierte Infos</b
                              >
                            </p>
                          </div>
                          <div
                            class="w-[56.3px] absolute my-0 mx-[!important] bottom-[-27.3px] left-[0.3px] text-6xs tracking-[0.09px] leading-[140%] text-primary-main-1 text-left inline-block z-[1]"
                          >
                            <p class="m-0 font-source-sans-pro">22.08.2023</p>
                            <p class="m-0">
                              <b
                                class="[text-decoration:underline] font-source-sans-pro"
                                >Detaillierte Infos</b
                              >
                            </p>
                          </div>
                        </div>
                        <div
                          class="w-[59.6px] flex-1 relative text-6xs tracking-[0.09px] leading-[140%] text-primary-main-1 text-left inline-block z-[2]"
                        >
                          <p class="m-0 font-source-sans-pro">14.03.2023</p>
                          <p class="m-0">
                            <b
                              class="[text-decoration:underline] font-source-sans-pro"
                              >Detaillierte Infos</b
                            >
                          </p>
                          <p class="m-0">
                            <b
                              class="[text-decoration:underline] font-source-sans-pro"
                              >&nbsp;</b
                            >
                          </p>
                        </div>
                      </div>
                      <div
                        class="h-[73px] w-[45px] flex flex-col items-start justify-start gap-[9px]"
                      >
                        <div
                          class="self-stretch flex-1 rounded-11xs flex flex-row items-center justify-center p-[5px] border-[0.5px] border-solid border-primary-main-blue"
                        >
                          <div
                            class="self-stretch w-[29px] relative text-6xs tracking-[0.25px] leading-[7.01px] uppercase font-medium font-roboto text-primary-main-blue text-center flex items-center justify-center"
                          >
                            Buchen
                          </div>
                        </div>
                        <div
                          class="self-stretch flex-1 rounded-11xs flex flex-row items-center justify-center p-[5px] border-[0.5px] border-solid border-action-states-light-mode-disabled"
                        >
                          <div
                            class="self-stretch w-[29px] relative text-6xs tracking-[0.25px] leading-[7.01px] uppercase font-medium font-roboto text-text-color-light-mode-disabled text-center flex items-center justify-center"
                          >
                            Buchen
                          </div>
                        </div>
                        <div
                          class="self-stretch flex-1 rounded-11xs flex flex-row items-center justify-center p-[5px] border-[0.5px] border-solid border-action-states-light-mode-disabled"
                        >
                          <div
                            class="self-stretch w-[29px] relative text-6xs tracking-[0.25px] leading-[7.01px] uppercase font-medium font-roboto text-text-color-light-mode-disabled text-center flex items-center justify-center"
                          >
                            Buchen
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </form>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import NavigationBar from "../components/NavigationBar.vue";
  import ContentComparison from "../components/ContentComparison.vue";
  import Frame from "../components/Frame.vue";
  import NavFooter from "../components/NavFooter.vue";
  import Experience from "../components/Experience.vue";
  import NavLine from "../components/NavLine.vue";

  export default defineComponent({
    name: "Page1",
    components: {
      NavigationBar,
      ContentComparison,
      Frame,
      NavFooter,
      Experience,
      NavLine,
    },
    methods: {
      onDetaillierteInfosTextClick() {
        // Please sync "Dashboard 1280px Draft 26" to the project
      },
    },
  });
</script>
