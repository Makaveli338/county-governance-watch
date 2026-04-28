<template>
  <section
    class="bg-[#F4F8F7] h-full w-full pt-8 space-y-8 sm:space-y-13.5 text-white pb-13.5"
  >
    <Header />
    <!--Top hero section-->
    <div class="section mx-auto px-6">
      <!--Text container-->
      <div class="mx-auto max-w-4xl text-center">
        <div class="space-y-4">
          <h2 class="font-semibold text-3xl sm:text-4xl text">
            <span class="text-primary"> Empowering</span> Citizens,
            <span class="text-secondary"> Strengthening</span> County
            Governance.
          </h2>
          <p class="text-xl text-[#6F8F88] max-w-3xl mx-auto">
            We support women, youth, and persons with disabilities to actively
            engage in county governance and shape sustainable development
            outcomes
          </p>
        </div>

        <button class="primary-btn mx-auto mt-6 hover:-translate-y-1">
          Donate
        </button>
      </div>

      <div class="grid sm:grid-cols-5 gap-4 items-end sm:-mt-12 mt-4">
        <!-- -->
        <div class="col-span-1 grid grid-cols-2 sm:grid-cols-1 gap-2.5 h-fit">
          <img src="/image1.png" alt="Speech" class="h-37.5 sm:h-auto w-full" />

          <div
            class="rounded-2xl px-6 bg-[#6F8F88] py-4 sm:py-8 text-white text-xl h-37.5 sm:h-auto"
          >
            <p class="leading-6.5">
              <span class="text-4xl font-semibold">33</span> /47
            </p>
            <p>Counties covered by our operation</p>
          </div>
        </div>

        <!-- -->
        <div
          class="col-span-1 object-bottom grid grid-cols-12 items-stretch sm:block"
        >
          <!-- -->
          <div class="col-span-8 p-6 rounded-2xl bg-[#E3ECE9] text-primary">
            <p
              class="text-xl font-semibold text-center leading-7.5 col-span-1 block sm:hidden"
            >
              Join 1000+ <br />
              people <br />
              building a <br />
              better <br />
              tommorrow
            </p>
          </div>
          <img
            src="/image2.png"
            alt="tug of war"
            class="col-span-4 h-full object-cover rounded-2xl"
          />
        </div>

        <!-- -->
        <div
          class="col-span-1 p-6 rounded-2xl bg-[#E3ECE9] text-primary hidden sm:block"
        >
          <p class="text-xl font-semibold text-center leading-7.5">
            Join 1000+ <br />
            people <br />
            building a <br />
            better <br />
            tommorrow
          </p>
        </div>

        <!-- -->
        <div class="col-span-1 object-bottom hidden sm:block">
          <img src="/image3.png" alt="civil education" />
        </div>

        <!-- -->
        <div class="col-span-1 h-fit flex flex-col gap-2.5">
          <div
            class="rounded-2xl px-10 bg-primary py-6 text-white text-xl h-fit sm:h-53.75 order-2 sm:order-1"
          >
            <p class="leading-7.5 hidden sm:block">
              Where citizens <br />
              shape <br />
              governance <br />
              and service <br />
              delivery.
            </p>

            <p class="leading-7.5 sm:hidden block text-center">
              Where citizens shape <br />
              governance and service <br />
              delivery.
            </p>
          </div>

          <img
            src="/Image4.png"
            alt="hands"
            class="h-25 sm:h-full w-full object-cover rounded-2xl order-1 sm:order-2"
          />
        </div>
      </div>
    </div>

    <!--About our organization-->
    <div class="space-y-6 section mx-auto px-6">
      <div class="flex justify-between flex-col sm:flex-row gap-4">
        <div class="space-y-2.5">
          <p class="text-primary font-medium text-xl sm:text-2xl">
            About <br />
            Our Organization
          </p>
          <div class="w-20 bg-secondary h-1.5 rounded-full"></div>
        </div>

        <p
          data-aos="fade-left"
          class="text-[#6F8F88] max-w-md text-sm sm:text-lg"
        >
          We promote transparent, accountable county governance by empowering
          citizens and strengthening public participation across Kenya’s
          devolved units.
        </p>
      </div>

      <div data-aos="fade-up" class="grid grid-cols-12 gap-6 min-h-105">
        <!-- LEFT: Image -->
        <div class="col-span-full sm:col-span-8 rounded-2xl overflow-hidden">
          <div
            class="bg-[url(/image5.png)] bg-cover bg-center h-full w-full px-6 pb-7 flex items-end pt-32"
          >
            <div class="space-y-2.5 sm:space-y-4 text-white">
              <p class="text-base sm:text-lg font-medium">Our Story</p>

              <div class="space-y-2 text-sm max-w-[90%]">
                <p>
                  County Governance Watch (CGW) is a Kenyan NGO promoting
                  transparent, accountable, and inclusive county governance to
                  advance socio-economic and sustainable development.
                </p>
                <p>
                  We empower women, youth, and persons with disabilities through
                  education and capacity building, strengthen public
                  participation, and support effective service delivery.
                </p>
                <p>
                  CGW operates in 33 counties, working with citizens and
                  institutions to improve governance, accountability, and
                  decision-making across Kenya’s devolved units.
                </p>
              </div>
            </div>
          </div>
        </div>

        <!-- RIGHT: Cards -->
        <div
          class="col-span-full sm:col-span-4 flex flex-col gap-2.5 sm:gap-6 h-full text"
        >
          <!-- Mission -->
          <div class="flex-1 rounded-2xl bg-[#E1F4EC] px-6 py-6 flex items-end">
            <div class="space-y-2">
              <p class="text-lg font-medium">Our Mission</p>
              <p class="text-sm">
                To empower citizen engagement for quality service delivery,
                sustainable development, and peace.
              </p>
            </div>
          </div>

          <!-- Vision -->
          <div class="flex-1 rounded-2xl bg-[#EFE1C2] px-6 py-6 flex items-end">
            <div class="space-y-2">
              <p class="text-lg font-medium">Our Vision</p>
              <p class="text-sm">
                Empowered citizens enjoying high-quality, efficient, and
                transparent service delivery.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!--Our core values-->
    <div class="space-y-13.5">
      <div
        data-aos="fade-up"
        data-aos-delay="200"
        class="max-w-3xl mx-auto space-y-2.5 sm:space-y-3 text-center"
      >
        <p class="text-lg sm:text-xl text-primary font-medium">
          Our Core Values
        </p>
        <p class="font-medium text-[#6F8F88] text-sm sm:text-base">
          At CGW, our <span class="text-primary"> values</span> are not just
          words; they are the guiding principles that define our character and
          drive our actions. We embody a culture represented by the acronym
          <span class="text-primary">IA-CEE,</span> reflecting our unwavering
          commitment to
          <span class="text-primary"
            >Integrity, Accountability, Collaboration, Excellence</span
          >
          and <span class="text-primary">Empowerment.</span>
        </p>
      </div>

      <!--Key areas to focus on-->
      <div class="bg-primary w-full py-8 sm:py-11.5 px-8 sm:px-14">
        <div class="section mx-auto space-y-8">
          <div class="space-y-2.5 text-center">
            <p class="text-lg sm:text-xl font-medium">
              Key Areas of <span class="text-secondary"> Focus</span>
            </p>
            <p class="text-sm sm:text-base">
              The core thematic areas that shape our programs and priorities.
            </p>
          </div>

          <div class="grid sm:grid-cols-7 gap-2.5 text-primary">
            <!-- -->
            <div
              class="bg-white rounded-2xl relative overflow-hidden h-25 sm:min-h-67.5 flex items-center sm:items-end sm:px-3 py-13 hover:scale-105 gap-6 sm:gap-0 transition-all duration-150 cursor-pointer"
            >
              <img
                src="/circle1.png"
                alt=""
                class="absolute top-0 left-0 hidden sm:block"
              />
              <img src="/mobile1.png" alt="" class="h-25 block sm:hidden" />

              <p class="relative leading-5 hidden sm:block">
                Devolution <br />
                & <br />
                County Participation
              </p>

              <p class="relative leading-5 sm:hidden block">
                Devolution & <br />
                County Participation
              </p>
            </div>
            <!-- -->
            <div
              class="bg-white rounded-2xl relative overflow-hidden h-25 sm:min-h-67.5 flex items-center gap-6 sm:gap-0 px-0 sm:items-end sm:px-3 py-13 hover:scale-105 transition-all duration-150 cursor-pointer"
            >
              <img
                src="/circle2.png"
                alt=""
                class="absolute top-0 left-0 hidden sm:block"
              />
              <img src="/mobile2.png" alt="" class="h-25 block sm:hidden" />

              <p class="relative leading-5 hidden sm:block">
                Inclusive <br />
                Governance & <br />
                Disability Rights
              </p>

              <p class="relative leading-5 sm:hidden block">
                Inclusive Governance <br />
                & Disability Rights
              </p>
            </div>

            <!-- -->
            <div
              class="bg-white rounded-2xl relative overflow-hidden h-25 sm:min-h-67.5 flex items-center gap-6 sm:gap-0 px-0 sm:items-end sm:px-3 py-13 hover:scale-105 transition-all duration-150 cursor-pointer"
            >
              <img
                src="/circle3.png"
                alt=""
                class="absolute top-0 left-0 hidden sm:block"
              />
              <img src="/mobile3.png" alt="" class="h-25 block sm:hidden" />

              <p class="relative leading-5 hidden sm:block">
                Peace <br />
                & <br />
                Human Security
              </p>

              <p class="relative leading-5 sm:hidden block">
                Peace & <br />
                Human Security
              </p>
            </div>

            <!-- -->
            <div
              class="bg-white rounded-2xl relative overflow-hidden h-25 sm:min-h-67.5 flex items-center gap-6 sm:gap-0 px-0 sm:items-end sm:px-3 py-13 hover:scale-105 transition-all duration-150 cursor-pointer"
            >
              <img
                src="/circle4.png"
                alt=""
                class="absolute top-0 left-0 hidden sm:block"
              />
              <img src="/mobile4.png" alt="" class="h-25 block sm:hidden" />

              <p class="relative leading-5">
                Governance <br />
                Performance <br />
                Tracking
              </p>
            </div>

            <!-- -->
            <div
              class="bg-white rounded-2xl relative overflow-hidden h-25 sm:min-h-67.5 flex items-center gap-6 sm:gap-0 px-0 sm:items-end sm:px-3 py-13 hover:scale-105 transition-all duration-150 cursor-pointer"
            >
              <img
                src="/circle5.png"
                alt=""
                class="absolute top-0 left-0 hidden sm:block"
              />
              <img src="/mobile5.png" alt="" class="h-25 block sm:hidden" />

              <p class="relative leading-5">
                Elections <br />
                & <br />
                Legislation
              </p>
            </div>

            <!-- -->
            <div
              class="bg-white rounded-2xl relative overflow-hidden h-25 sm:min-h-67.5 flex items-center gap-6 sm:gap-0 px-0 sm:items-end sm:px-3 py-13 hover:scale-105 transition-all duration-150 cursor-pointer"
            >
              <img
                src="/circle6.png"
                alt=""
                class="absolute top-0 left-0 hidden sm:block"
              />
              <img src="/mobile6.png" alt="" class="h-25 block sm:hidden" />

              <p class="relative leading-5">
                Youth & <br />
                Women <br />
                Empowerment
              </p>
            </div>

            <!-- -->
            <div
              class="bg-white rounded-2xl relative overflow-hidden h-25 sm:min-h-67.5 flex items-center gap-6 sm:gap-0 px-0 sm:items-end sm:px-3 py-13 hover:scale-105 transition-all duration-150 cursor-pointer"
            >
              <img
                src="/circle7.png"
                alt=""
                class="absolute top-0 left-0 hidden sm:block"
              />
              <img src="/mobile7.png" alt="" class="h-25 block sm:hidden" />

              <p class="relative leading-5">
                Climate <br />
                Action
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!--Meet our team-->
    <div class="sm:space-y-16 space-y-5">
      <div class="w-full text-center flex flex-col items-center gap-2.5">
        <p class="text-xl sm:text-2xl font-medium text-primary">
          Meet Our Team
        </p>
        <div class="w-20 bg-secondary h-1.5 rounded-full"></div>
      </div>

      <div class="space-y-2.5 sm:space-y-6 max-w-250 mx-auto px-5 sm:px-0">
        <div class="space-y-2.5 sm:hidden flex flex-col items-center">
          <img src="/exec.png" alt="Executive Director" class="h-37.5" />

          <div class="space-y-3 text-center">
            <div class="space-y-1.5">
              <p class="text-base sm:text-lg text-primary font-medium">
                Kevin Osido, OGW
              </p>
              <p class="text text-xs sm:text-sm leading-3">
                Executive Director
              </p>
            </div>

            <div class="flex gap-1.5 justify-center">
              <a href="">
                <img src="/x.svg" alt="" class="h-5 w-5" />
              </a>

              <a href="">
                <img src="/linkedin.svg" alt="" class="h-5 w-5" />
              </a>
            </div>
          </div>
        </div>

        <!-- Executive Director-->
        <div
          class="bg-white rounded-[20px] sm:py-9 sm:pr-18.5 sm:pl-24 py-4 px-5 flex gap-14 sm:hover:scale-105 cursor-pointer duration-200 transition-all"
        >
          <!--Text container-->
          <div
            class="gap-2.5 text-sm leading-5.5 text flex flex-col justify-center"
          >
            <p>
              Kevin Osido is a Governance Specialist and the Executive Director
              of County Governance Watch (CGW), where he leads initiatives that
              promote socio-economic and political development across Kenya’s
              counties. His work focuses on civic education, capacity building
              for citizens and county government officers, and strengthening
              public participation to improve governance, accountability, and
              service delivery.
            </p>
            <p class="hidden sm:block">
              Kevin holds a Master of Science in Governance and has extensive
              experience working with national and county governments,
              development partners, and community networks. A Governance
              Trainer, he has contributed to governance and leadership
              initiatives in Kenya, East Africa, and the Great Lakes Region. He
              also serves as National Chairman of the ICGLR Civil Society Forum
              – Kenya Chapter and Regional Chairman for Democracy and Good
              Governance, representing 12 countries.
            </p>
          </div>

          <div class="space-y-2.5 -mt-16 hidden sm:block">
            <img src="/exec.png" alt="Executive Director" />

            <div class="space-y-3 text-center">
              <div class="space-y-1.5">
                <p class="text-lg text-primary font-medium">Kevin Osido, OGW</p>
                <p class="text text-sm">Executive Director</p>
              </div>

              <div class="flex gap-1.5 justify-center">
                <a href="">
                  <img src="/x.svg" alt="" class="h-5 w-5" />
                </a>

                <a href="">
                  <img src="/linkedin.svg" alt="" class="h-5 w-5" />
                </a>
              </div>
            </div>
          </div>
        </div>

        <!--Team members-->
        <div class="flex flex-col sm:flex-row gap-2.5 sm:gap-4 mx-auto mt-2">
          <div class="flex gap-4">
            <!-- -->
            <div
              class="bg-white border-[#ECECEC] rounded-2xl relative overflow-hidden h-82.5 w-59.5 flex items-end px-6 pb-9 transition-all duration-150 cursor-pointer"
            >
              <img src="/programs.png" alt="" class="absolute top-0 left-0" />

              <div class="space-y-2.5">
                <p class="text-xl text-primary font-medium">Edna K. Miriti</p>
                <p class="text-sm text">Programs Officer</p>
              </div>
            </div>

            <!-- -->
            <div
              class="bg-white border-[#ECECEC] rounded-2xl relative overflow-hidden h-82.5 w-59.5 flex items-end px-6 pb-9 transition-all duration-150 cursor-pointer"
            >
              <img src="/programs2.png" alt="" class="absolute top-0 left-0" />

              <div class="space-y-2.5">
                <p class="text-xl text-primary font-medium">Daniel Muia</p>
                <p class="text-sm text">Programs Officer</p>
              </div>
            </div>
          </div>

          <div class="flex gap-4">
            <!-- -->
            <div
              class="bg-white border-[#ECECEC] rounded-2xl relative overflow-hidden h-82.5 w-59.5 flex items-end px-6 pb-9 transition-all duration-150 cursor-pointer"
            >
              <img src="/programs3.png" alt="" class="absolute top-0 left-0" />

              <div class="space-y-2.5">
                <p class="text-xl text-primary font-medium">Hawi Rapudo</p>
                <p class="text-sm text">Programs Officer</p>
              </div>
            </div>

            <!-- -->
            <div
              class="bg-white border-[#ECECEC] rounded-2xl relative overflow-hidden h-82.5 w-59.5 flex items-end px-6 pb-9 transition-all duration-150 cursor-pointer"
            >
              <img src="/programs4.png" alt="" class="absolute top-0 left-0" />

              <div class="space-y-2.5">
                <p class="text-xl text-primary font-medium">Romeo Odumbe</p>
                <p class="text-sm text">Programs Officer</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!--Posts-->
    <div class="section mx-auto space-y-6 px-6">
      <div class="w-full text-center flex flex-col items-center gap-2.5">
        <p class="text-2xl font-medium text-primary">Posts</p>
        <div class="w-20 bg-secondary h-1.5 rounded-full"></div>
      </div>

      <div class="flex gap-4 sm:grid sm:grid-cols-5 overflow-x-auto sm:overflow-x-clip pb-2">
        <!---->
        <div class="min-w-72 sm:min-w-full bg-white border rounded-2xl border-[#ECECEC] space-y-11 relative">
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
              Unlocking The Power Of Women In Climate Action And Resilience
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post1.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end absolute bottom-0 w-full"
          >
            <button
              class="bg-[#00000099] flex gap-1.5 px-1.5 py-1.5 items-center rounded-full group"
            >
              <p class="text-xs font-medium">Read More</p>
              <div
                class="size-5 rounded-full bg-white flex items-center justify-center"
              >
                <svg
                  class="group-hover:translate-x-0.5"
                  width="16"
                  height="16"
                  viewBox="0 0 16 16"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M3.33301 8.00016H12.6663M12.6663 8.00016L7.99967 3.3335M12.6663 8.00016L7.99967 12.6668"
                    stroke="black"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
              </div>
            </button>
          </div>
        </div>

        <!---->
        <div
          class="min-w-72 sm:min-w-full bg-white border rounded-2xl border-[#ECECEC] space-y-11 flex flex-col justify-between"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">GPPAC Experts Meeting 2016</p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post2.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end"
          >
            <button
              class="bg-[#00000099] flex gap-1.5 px-1.5 py-1.5 items-center rounded-full group"
            >
              <p class="text-xs font-medium">Read More</p>
              <div
                class="size-5 rounded-full bg-white flex items-center justify-center"
              >
                <svg
                  class="group-hover:translate-x-0.5"
                  width="16"
                  height="16"
                  viewBox="0 0 16 16"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M3.33301 8.00016H12.6663M12.6663 8.00016L7.99967 3.3335M12.6663 8.00016L7.99967 12.6668"
                    stroke="black"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
              </div>
            </button>
          </div>
        </div>

        <!---->
        <div
          class="min-w-72 sm:min-w-full bg-white border rounded-2xl border-[#ECECEC] space-y-11 flex flex-col justify-between"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">CGW Strategic Plan 2016-2021</p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post3.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end"
          >
            <button
              class="bg-[#00000099] flex gap-1.5 px-1.5 py-1.5 items-center rounded-full group"
            >
              <p class="text-xs font-medium">Read More</p>
              <svg
                class="group-hover:translate-x-0.5"
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect width="20" height="20" rx="10" fill="white" />
                <path
                  d="M5.33301 10.0002H14.6663M14.6663 10.0002L9.99967 5.3335M14.6663 10.0002L9.99967 14.6668"
                  stroke="black"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

        <!---->
        <div class="min-w-72 sm:min-w-full bg-white border rounded-2xl border-[#ECECEC] space-y-11">
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
              Mainstreaming Prevention Of Violent Extremism In Nairobi City
              County Departments
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post4.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end"
          >
            <button
              class="bg-[#00000099] flex gap-1.5 px-1.5 py-1.5 items-center rounded-full group"
            >
              <p class="text-xs font-medium">Read More</p>
              <div
                class="size-5 rounded-full bg-white flex items-center justify-center"
              >
                <svg
                  class="group-hover:translate-x-0.5"
                  width="16"
                  height="16"
                  viewBox="0 0 16 16"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M3.33301 8.00016H12.6663M12.6663 8.00016L7.99967 3.3335M12.6663 8.00016L7.99967 12.6668"
                    stroke="black"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
              </div>
            </button>
          </div>
        </div>
        <!---->
        <div class="min-w-72 sm:min-w-full bg-white border rounded-2xl border-[#ECECEC] space-y-11">
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
              Tabasamu Peace and Social Cohesion Sessions in Kibra and Mathare
              Sub-Counties
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post5.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end"
          >
            <button
              class="bg-[#00000099] flex gap-1.5 px-1.5 py-1.5 items-center rounded-full group"
            >
              <p class="text-xs font-medium">Read More</p>
              <div
                class="size-5 rounded-full bg-white flex items-center justify-center"
              >
                <svg
                  class="group-hover:translate-x-0.5"
                  width="16"
                  height="16"
                  viewBox="0 0 16 16"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M3.33301 8.00016H12.6663M12.6663 8.00016L7.99967 3.3335M12.6663 8.00016L7.99967 12.6668"
                    stroke="black"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
              </div>
            </button>
          </div>
        </div>

      </div>
      <div class="flex justify-center mt-8">
        <button class="primary-btn">See all posts</button>
      </div>
    </div>

    <!--Our partners-->
    <div class="space-y-3 section mx-auto text-center pt-7 px-4">
      <p class="text-primary text-xl sm:text-2xl font-medium">Our Partners</p>

      <div class="overflow-hidden">
        <div class="flex items-center gap-12 marquee">
          <!-- original set -->
          <img
            src="/kiambu.svg"
            alt="county govt of Kiambu"
            class="w-auto shrink-0"
          />
          <img
            src="/city-council.svg"
            alt="city council"
            class="w-auto shrink-0"
          />
          <img src="/corps.svg" alt="mercy corps" class="w-auto shrink-0" />
          <img
            src="/auditor-general.svg"
            alt="Office of the auditor general"
            class="w-auto shrink-0"
          />
          <img
            src="/kenya.svg"
            alt="Republic of Kenya"
            class="w-auto shrink-0"
          />
          <img
            src="/ngaaf.svg"
            alt="National government affirmative action fund"
            class="w-auto shrink-0"
          />
          <img
            src="/terrorism.svg"
            alt="National counter terrorism center"
            class="w-auto shrink-0"
          />
          <img
            src="/disabilities.svg"
            alt="National council for persons with disabilities"
            class="w-auto shrink-0"
          />
          <!-- duplicate set for seamless loop -->
          <img
            src="/kiambu.svg"
            alt=""
            aria-hidden="true"
            class="w-auto shrink-0"
          />
          <img
            src="/city-council.svg"
            alt=""
            aria-hidden="true"
            class="w-auto shrink-0"
          />
          <img
            src="/corps.svg"
            alt=""
            aria-hidden="true"
            class="w-auto shrink-0"
          />
          <img
            src="/auditor-general.svg"
            alt=""
            aria-hidden="true"
            class="w-auto shrink-0"
          />
          <img
            src="/kenya.svg"
            alt=""
            aria-hidden="true"
            class="w-auto shrink-0"
          />
          <img
            src="/ngaaf.svg"
            alt=""
            aria-hidden="true"
            class="w-auto shrink-0"
          />
          <img
            src="/terrorism.svg"
            alt=""
            aria-hidden="true"
            class="w-auto shrink-0"
          />
          <img
            src="/disabilities.svg"
            alt=""
            aria-hidden="true"
            class="w-auto shrink-0"
          />
        </div>
      </div>
    </div>

    <!--Contact us-->
    <div id="contact" class="space-y-3 text-center">
      <p class="text-2xl font-medium text-primary">Contact Us</p>

      <div class="section mx-auto grid grid-cols-12 text-start sm:pl-9 px-5">
        <!--col-span-9-->
        <div class="bg-white rounded-2xl px-4 py-5 sm:pl-12 sm:py-12 col-span-full sm:col-span-9 h-fit">
          <div class="sm:max-w-lg space-y-6">
            <div class="space-y-0.5 pb-4 border-b border-[#DFE0E2] text-start">
              <p class="text-base sm:text-lg font-medium text-primary">
                How can we assist you <span class="text-xl"> today?</span>
              </p>
              <p class="text-xs sm:text-sm text">
                Feel free to reach out to us with your inquiries.
              </p>
            </div>

            <!--Input form-->
            <div class="space-y-2.5">
              <div class="space-y-1">
                <p class="text-sm text">Name</p>
                <input
                  type="text"
                  placeholder="John Paul"
                  class="w-full border border-[#D1D5DB] rounded-md px-4 py-3 placeholder:text-[#D1D5DB] focus:outline-none focus:ring-2 focus:ring-[#6F8F88] bg-white"
                />
              </div>

              <div class="space-y-1">
                <p class="text-sm text">Email</p>
                <input
                  type="email"
                  placeholder="papapaul@mail.com"
                  class="w-full border border-[#D1D5DB] rounded-md px-4 py-3 placeholder:text-[#D1D5DB] focus:outline-none focus:ring-2 focus:ring-[#6F8F88] bg-white"
                />
              </div>

              <div class="space-y-1">
                <p class="text-sm text">Write your message</p>
                <textarea
                  placeholder="Your message"
                  rows="5"
                  class="w-full border border-[#D1D5DB] rounded-md px-4 py-3 placeholder:text-[#D1D5DB] focus:outline-none focus:ring-2 focus:ring-[#6F8F88] bg-white resize-none"
                ></textarea>
              </div>
            </div>

            <div class="flex justify-end">
              <button class="primary-btn">Send Message</button>
            </div>
          </div>
        </div>

        <!--col-span-3-->
        <div
          class="col-span-full sm:col-span-3 bg-primary px-5.5 w-87.5 rounded-2xl mt-4 sm:mt-12 sm:-ml-50 flex flex-col justify-center gap-4 py-5.5"
        >
          <p class="text-lg sm:text-xl font-medium">
            Hi, we are always here to <br />
            assist you.
          </p>

          <div class="space-y-2">
            <!---->
            <div
              class="px-6 py-4 flex items-center gap-4 bg-[#FFFFFF33] rounded-2xl"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M12 12.5C13.6569 12.5 15 11.1569 15 9.5C15 7.84315 13.6569 6.5 12 6.5C10.3431 6.5 9 7.84315 9 9.5C9 11.1569 10.3431 12.5 12 12.5Z"
                  stroke="white"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M12 22C14 18 20 15.4183 20 10C20 5.58172 16.4183 2 12 2C7.58172 2 4 5.58172 4 10C4 15.4183 10 18 12 22Z"
                  stroke="white"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>

              <div class="space-y-1">
                <p class="text-sm font-medium">Visit us:</p>

                <div class="text-sm space-y-0.5">
                  <p>Governance Suite ILU Compound,</p>
                  <p>Lenana Rd,Hurligham</p>
                </div>
              </div>
            </div>

            <!---->
            <div
              class="px-6 py-4 flex items-center gap-4 bg-[#FFFFFF33] rounded-2xl"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M8.38028 8.85335C9.07627 10.303 10.0251 11.6616 11.2266 12.8632C12.4282 14.0648 13.7869 15.0136 15.2365 15.7096C15.3612 15.7694 15.4235 15.7994 15.5024 15.8224C15.7828 15.9041 16.127 15.8454 16.3644 15.6754C16.4313 15.6275 16.4884 15.5704 16.6027 15.4561C16.9523 15.1064 17.1271 14.9316 17.3029 14.8174C17.9658 14.3864 18.8204 14.3864 19.4833 14.8174C19.6591 14.9316 19.8339 15.1064 20.1835 15.4561L20.3783 15.6509C20.9098 16.1824 21.1755 16.4481 21.3198 16.7335C21.6069 17.301 21.6069 17.9713 21.3198 18.5389C21.1755 18.8242 20.9098 19.09 20.3783 19.6214L20.2207 19.779C19.6911 20.3087 19.4263 20.5735 19.0662 20.7757C18.6667 21.0001 18.0462 21.1615 17.588 21.1601C17.1751 21.1589 16.8928 21.0788 16.3284 20.9186C13.295 20.0576 10.4326 18.4332 8.04466 16.0452C5.65668 13.6572 4.03221 10.7948 3.17124 7.76144C3.01103 7.19699 2.93092 6.91477 2.9297 6.50182C2.92833 6.0436 3.08969 5.42311 3.31411 5.0236C3.51636 4.66357 3.78117 4.39876 4.3108 3.86913L4.46843 3.7115C4.99987 3.18006 5.2656 2.91433 5.55098 2.76999C6.11854 2.48292 6.7888 2.48292 7.35636 2.76999C7.64174 2.91433 7.90747 3.18006 8.43891 3.7115L8.63378 3.90637C8.98338 4.25597 9.15819 4.43078 9.27247 4.60655C9.70347 5.26945 9.70347 6.12403 9.27247 6.78692C9.15819 6.96269 8.98338 7.1375 8.63378 7.4871C8.51947 7.60142 8.46231 7.65857 8.41447 7.72538C8.24446 7.96281 8.18576 8.30707 8.26748 8.58743C8.29048 8.66632 8.32041 8.72866 8.38028 8.85335Z"
                  stroke="white"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>

              <div class="space-y-1">
                <p class="text-sm font-medium">Call us:</p>

                <div class="text-sm gap-0.5 flex flex-col">
                  <a
                    class="cursor-pointer relative inline-block no-underline w-fit after:content-[''] after:absolute after:w-full after:scale-x-0 after:rounded after:h-[0.05em] after:bottom-0 after:left-0 after:bg-current after:origin-bottom-right after:transition-transform after:duration-200 after:ease-out hover:after:scale-x-100 hover:after:origin-bottom-left"
                    href="tel:020 4404140"
                    >020 4404140</a
                  >
                  <a
                    class="cursor-pointer relative inline-block no-underline w-fit after:content-[''] after:absolute after:w-full after:scale-x-0 after:rounded after:h-[0.05em] after:bottom-0 after:left-0 after:bg-current after:origin-bottom-right after:transition-transform after:duration-200 after:ease-out hover:after:scale-x-100 hover:after:origin-bottom-left"
                    href="tel:+254 720 576 696"
                    >+254 720 576 696</a
                  >
                </div>
              </div>
            </div>

            <!---->
            <div
              class="px-6 py-4 flex items-center gap-4 bg-[#FFFFFF33] rounded-2xl"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M13.744 2.63346L21.272 7.52667C21.538 7.69957 21.671 7.78602 21.7674 7.90134C21.8527 8.00342 21.9167 8.12149 21.9558 8.24865C22 8.39229 22 8.55092 22 8.86818V16.1999C22 17.88 22 18.7201 21.673 19.3619C21.3854 19.9263 20.9265 20.3853 20.362 20.6729C19.7202 20.9999 18.8802 20.9999 17.2 20.9999H6.8C5.11984 20.9999 4.27976 20.9999 3.63803 20.6729C3.07354 20.3853 2.6146 19.9263 2.32698 19.3619C2 18.7201 2 17.88 2 16.1999V8.86818C2 8.55092 2 8.39229 2.04417 8.24865C2.08327 8.12149 2.14735 8.00342 2.23265 7.90134C2.32901 7.78602 2.46201 7.69957 2.72802 7.52667L10.256 2.63346M13.744 2.63346C13.1127 2.22315 12.7971 2.01799 12.457 1.93817C12.1564 1.86761 11.8436 1.86761 11.543 1.93817C11.2029 2.01799 10.8873 2.22315 10.256 2.63346M13.744 2.63346L20.9681 7.32913C21.312 7.55268 21.484 7.66445 21.5435 7.8062C21.5956 7.93008 21.5956 8.06969 21.5435 8.19356C21.484 8.33531 21.312 8.44709 20.9681 8.67064L13.744 13.3663C13.1127 13.7766 12.7971 13.9818 12.457 14.0616C12.1564 14.1321 11.8436 14.1321 11.543 14.0616C11.2029 13.9818 10.8873 13.7766 10.256 13.3663L3.03193 8.67064C2.68801 8.44709 2.51604 8.33531 2.45649 8.19356C2.40444 8.06969 2.40444 7.93008 2.45649 7.8062C2.51604 7.66445 2.68801 7.55268 3.03193 7.32913L10.256 2.63346"
                  stroke="white"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>

              <div class="space-y-1">
                <p class="text-sm font-medium">Email us:</p>

                <div class="text-sm">
                  <a
                    class="cursor-pointer relative inline-block no-underline w-fit after:content-[''] after:absolute after:w-full after:scale-x-0 after:rounded after:h-[0.05em] after:bottom-0 after:left-0 after:bg-current after:origin-bottom-right after:transition-transform after:duration-200 after:ease-out hover:after:scale-x-100 hover:after:origin-bottom-left"
                    href="mail:info@cgwkenya.com"
                    >info@cgwkenya.com</a
                  >
                </div>
              </div>
            </div>

            <!---->
            <div
              class="px-6 py-4 flex items-center gap-4 bg-[#FFFFFF33] rounded-2xl"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M21.5 18L14.8571 12M9.14286 12L2.50003 18M2 7L10.1649 12.7154C10.8261 13.1783 11.1567 13.4097 11.5163 13.4993C11.8339 13.5785 12.1661 13.5785 12.4837 13.4993C12.8433 13.4097 13.1739 13.1783 13.8351 12.7154L22 7M6.8 20H17.2C18.8802 20 19.7202 20 20.362 19.673C20.9265 19.3854 21.3854 18.9265 21.673 18.362C22 17.7202 22 16.8802 22 15.2V8.8C22 7.11984 22 6.27976 21.673 5.63803C21.3854 5.07354 20.9265 4.6146 20.362 4.32698C19.7202 4 18.8802 4 17.2 4H6.8C5.11984 4 4.27976 4 3.63803 4.32698C3.07354 4.6146 2.6146 5.07354 2.32698 5.63803C2 6.27976 2 7.11984 2 8.8V15.2C2 16.8802 2 17.7202 2.32698 18.362C2.6146 18.9265 3.07354 19.3854 3.63803 19.673C4.27976 20 5.11984 20 6.8 20Z"
                  stroke="white"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>

              <div class="space-y-1">
                <p class="text-sm font-medium">Mail us:</p>

                <div>
                  <p class="font-medium">
                    P.O. Box 104578- 00101, Nairobi-Kenya
                  </p>
                </div>
              </div>
            </div>
          </div>

          <div class="border-t border-white pt-2.5 space-y-1.5">
            <p class="text-sm font-medium">Connect with us</p>

            <div class="flex gap-2">
              <a href="" class="hover:translate-y-0.5"
                ><svg
                  width="23"
                  height="23"
                  viewBox="0 0 23 23"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M11.5219 23H11.4713C5.1461 23 0 17.8524 0 11.5253V11.4747C0 5.14762 5.1461 0 11.4713 0H11.5219C17.8471 0 22.9932 5.14762 22.9932 11.4747V11.5253C22.9932 17.8524 17.8471 23 11.5219 23ZM11.4713 0.778526C5.57494 0.778526 0.778297 5.57659 0.778297 11.4747V11.5253C0.778297 17.4234 5.57494 22.2215 11.4713 22.2215H11.5219C17.4183 22.2215 22.2149 17.4234 22.2149 11.5253V11.4747C22.2149 5.57659 17.4183 0.778526 11.5219 0.778526H11.4713Z"
                    fill="white"
                  />
                  <path
                    d="M4.88348 5.42432L10.0062 12.2753L4.85156 17.8457H6.01201L10.5254 12.969L14.1717 17.8457H18.12L12.7092 10.6093L17.5075 5.42432H16.347L12.1909 9.91563L8.83255 5.42432H4.88424H4.88348ZM6.5895 6.27914H8.40293L16.4124 16.9909H14.599L6.5895 6.27914Z"
                    fill="white"
                  />
                </svg>
              </a>

              <a href="" class="hover:translate-y-0.5"
                ><svg
                  width="23"
                  height="23"
                  viewBox="0 0 23 23"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M11.5219 23H11.4713C5.14611 23 0 17.8524 0 11.5253V11.4747C0 5.14762 5.14611 0 11.4713 0H11.5219C17.8471 0 22.9932 5.14762 22.9932 11.4747V11.5253C22.9932 17.8524 17.8471 23 11.5219 23ZM11.4713 0.778526C5.57495 0.778526 0.778297 5.57658 0.778297 11.4747V11.5253C0.778297 17.4234 5.57495 22.2215 11.4713 22.2215H11.5219C17.4183 22.2215 22.2149 17.4234 22.2149 11.5253V11.4747C22.2149 5.57658 17.4183 0.778526 11.5219 0.778526H11.4713Z"
                    fill="white"
                  />
                  <path
                    d="M5.69403 7.77437C5.40139 7.50267 5.25586 7.16635 5.25586 6.76618C5.25586 6.36602 5.40217 6.0149 5.69403 5.74242C5.98667 5.47071 6.36337 5.33447 6.8249 5.33447C7.28643 5.33447 7.64834 5.47071 7.9402 5.74242C8.23284 6.01413 8.37838 6.3559 8.37838 6.76618C8.37838 7.17647 8.23207 7.50267 7.9402 7.77437C7.64756 8.04608 7.27631 8.18232 6.8249 8.18232C6.37349 8.18232 5.98667 8.04608 5.69403 7.77437ZM8.13244 9.33298V17.6632H5.50102V9.33298H8.13244Z"
                    fill="white"
                  />
                  <path
                    d="M16.8672 10.1544C17.4408 10.7773 17.7272 11.6321 17.7272 12.7205V17.5146H15.2281V13.0584C15.2281 12.5095 15.0857 12.0828 14.8016 11.7792C14.5175 11.4756 14.1346 11.323 13.6552 11.323C13.1758 11.323 12.7928 11.4748 12.5087 11.7792C12.2247 12.0828 12.0822 12.5095 12.0822 13.0584V17.5146H9.56836V9.30819H12.0822V10.3966C12.3367 10.0338 12.68 9.74727 13.1112 9.53629C13.5423 9.32531 14.0272 9.22021 14.5666 9.22021C15.527 9.22021 16.2944 9.53163 16.8672 10.1544Z"
                    fill="white"
                  />
                </svg>
              </a>

              <a href="" class="hover:translate-y-0.5"
                ><svg
                  width="23"
                  height="23"
                  viewBox="0 0 23 23"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M11.5219 23H11.4713C5.1461 23 0 17.8524 0 11.5253V11.4747C0 5.14762 5.1461 0 11.4713 0H11.5219C17.8471 0 22.9932 5.14762 22.9932 11.4747V11.5253C22.9932 17.8524 17.8471 23 11.5219 23ZM11.4713 0.778526C5.57494 0.778526 0.778297 5.57659 0.778297 11.4747V11.5253C0.778297 17.4234 5.57494 22.2215 11.4713 22.2215H11.5219C17.4183 22.2215 22.2149 17.4234 22.2149 11.5253V11.4747C22.2149 5.57659 17.4183 0.778526 11.5219 0.778526H11.4713Z"
                    fill="white"
                  />
                  <path
                    d="M13.0433 8.92123V11.3417H16.0366L15.5627 14.6021H13.0433V22.1141C12.5382 22.1842 12.0214 22.2208 11.4968 22.2208C10.8913 22.2208 10.2967 22.1725 9.71765 22.0791V14.6021H6.95703V11.3417H9.71765V8.38016C9.71765 6.54283 11.2065 5.05273 13.0441 5.05273V5.05428C13.0495 5.05428 13.0542 5.05273 13.0597 5.05273H16.0374V7.87256H14.0917C13.5134 7.87256 13.0441 8.342 13.0441 8.92045L13.0433 8.92123Z"
                    fill="white"
                  />
                </svg>
              </a>

              <a href="" class="hover:translate-y-0.5"
                ><svg
                  width="23"
                  height="23"
                  viewBox="0 0 23 23"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M11.5219 23H11.4713C5.1461 23 0 17.8524 0 11.5253V11.4747C0 5.14762 5.1461 0 11.4713 0H11.5219C17.8471 0 22.9932 5.14762 22.9932 11.4747V11.5253C22.9932 17.8524 17.8471 23 11.5219 23ZM11.4713 0.778526C5.57494 0.778526 0.778297 5.57659 0.778297 11.4747V11.5253C0.778297 17.4234 5.57494 22.2215 11.4713 22.2215H11.5219C17.4183 22.2215 22.2149 17.4234 22.2149 11.5253V11.4747C22.2149 5.57659 17.4183 0.778526 11.5219 0.778526H11.4713Z"
                    fill="white"
                  />
                  <path
                    d="M14.9351 4.91016H8.06115C6.16211 4.91016 4.61719 6.45553 4.61719 8.35514V14.6456C4.61719 16.5452 6.16211 18.0906 8.06115 18.0906H14.9351C16.8341 18.0906 18.379 16.5452 18.379 14.6456V8.35514C18.379 6.45553 16.8341 4.91016 14.9351 4.91016ZM5.83211 8.35514C5.83211 7.12584 6.83222 6.12543 8.06115 6.12543H14.9351C16.164 6.12543 17.1641 7.12584 17.1641 8.35514V14.6456C17.1641 15.8749 16.164 16.8753 14.9351 16.8753H8.06115C6.83222 16.8753 5.83211 15.8749 5.83211 14.6456V8.35514Z"
                    fill="white"
                  />
                  <path
                    d="M11.4984 14.7042C13.2644 14.7042 14.7019 13.2671 14.7019 11.4998C14.7019 9.73257 13.2651 8.29541 11.4984 8.29541C9.73166 8.29541 8.29492 9.73257 8.29492 11.4998C8.29492 13.2671 9.73166 14.7042 11.4984 14.7042ZM11.4984 9.51147C12.595 9.51147 13.4869 10.4037 13.4869 11.5006C13.4869 12.5976 12.595 13.4897 11.4984 13.4897C10.4018 13.4897 9.50985 12.5976 9.50985 11.5006C9.50985 10.4037 10.4018 9.51147 11.4984 9.51147Z"
                    fill="white"
                  />
                  <path
                    d="M14.9979 8.8127C15.4734 8.8127 15.861 8.42578 15.861 7.94932C15.861 7.47286 15.4742 7.08594 14.9979 7.08594C14.5216 7.08594 14.1348 7.47286 14.1348 7.94932C14.1348 8.42578 14.5216 8.8127 14.9979 8.8127Z"
                    fill="white"
                  />
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <Footer />
</template>

<script>
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";
</script>

<style scoped>
.marquee {
  animation: marquee 20s linear infinite;
  width: max-content;
}

@keyframes marquee {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-50%);
  }
}
</style>
