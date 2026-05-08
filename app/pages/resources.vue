<template>
  <section class="space-y-15">
    <header
      style="
        background-image: url(&quot;/resources.png&quot;);
        height: 258px;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
      "
      class="w-full h-62.5 sm:px-10 relative"
    >
      <div class="hidden sm:block" style="position: absolute; right: 85px; top: 60px">
        <img src="/resources2.png" alt="" />
      </div>

      <div class="pt-8 space-y-9 px-6 sm:px-0">
        <Header />

        <div class="max-w-6xl mx-auto">
          <p class="text-secondary text-4xl font-semibold leading-[100%]">
            Resources
          </p>
          <p class="text-sm text-white leading-5.5">
            Collection of Reports, Newsletters and strategic plans done by our
            Organization.
          </p>
        </div>
      </div>
    </header>

    <!--Body-->
    <div class="space-y-6 px-4 sm:px-6">
         <div
        class="max-w-6xl mx-auto gap-4 flex lg:grid grid-cols-4 overflow-x-auto lg:overflow-x-clip"
      >
        <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8 relative"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">2024 - 2028 Strategic Plan</p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post1.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end w-full absolute bottom-0"
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

        <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8 flex flex-col justify-between"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">Garrisa Job Fair and Exhibition</p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post2.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end"
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

        <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8 flex flex-col justify-between"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">Boroughs Public Participation Report</p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post3.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end"
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

         <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8 flex flex-col justify-between"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">CGW CITA  Report 2024</p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/cgw-cita.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end"
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>        
      </div>

      <div class="max-w-6xl mx-auto gap-4 flex lg:grid grid-cols-4 overflow-x-auto lg:overflow-x-clip">
        <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8 relative"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
             CLC Report 2024
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post4.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end absolute bottom-0 w-full"
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

        <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
              Inaugural Regional Citizens’ Accounta...
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/post5.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end "
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

          <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
            Kiambu Disability ACT TWG Workshop Re...
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/kiambu-disability-act.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end "
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

         <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
            Kiambu PWD ACT Regulation Incept...
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/kiambu-pwd-act.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end "
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

      </div>

       <div class="max-w-6xl mx-auto gap-4 flex lg:grid grid-cols-4 overflow-x-auto lg:overflow-x-clip">
         <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
            Kiambu County Governance Assesm...
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/kiambu-county-governance.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end "
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

        <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
              Report 2 on Localisation of Kenya National Act...
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/localisation.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end "
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

          <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
            Report on Technical Working Group Meeting
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/technical-working-group.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end "
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

         <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
            Report on Kenya National Action Plan
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/national-action-plan.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end "
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

      </div>

      <div class="max-w-6xl mx-auto gap-4 flex lg:grid sm:grid-cols-4 overflow-x-auto lg:overflow-x-clip">
         <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
           Kiambu Employability Summit Report 2024
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/kiambu-employability.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end "
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>

        <!---->
        <div
          class="w-72 shrink-0 bg-white border rounded-2xl border-[#ECECEC] space-y-8 relative"
        >
          <!--Text-->
          <div class="pt-6 px-4 space-y-1.5">
            <p class="font-medium text">
             CGW CITA  Report
            </p>
            <p class="text-xs text-[#6F8F88]">Jan 14, 2026</p>
          </div>

          <div
            class="bg-[url(/cgw-cita2.png)] h-37.5 bg-cover bg-center rounded-2xl bg-no-repeat px-4 pb-4.5 flex items-end absolute bottom-0 w-full"
          >
            <button class="primary-btn px-10 py-2.5">
              Preview
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2.01677 10.5944C1.90328 10.4147 1.84654 10.3248 1.81477 10.1863C1.79091 10.0822 1.79091 9.918 1.81477 9.8139C1.84654 9.67532 1.90328 9.58547 2.01677 9.40577C2.95461 7.92078 5.74617 4.16675 10.0003 4.16675C14.2545 4.16675 17.0461 7.92078 17.9839 9.40577C18.0974 9.58547 18.1541 9.67532 18.1859 9.8139C18.2098 9.918 18.2098 10.0822 18.1859 10.1863C18.1541 10.3248 18.0974 10.4147 17.9839 10.5944C17.0461 12.0794 14.2545 15.8334 10.0003 15.8334C5.74617 15.8334 2.95461 12.0794 2.01677 10.5944Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M10.0003 12.5001C11.381 12.5001 12.5003 11.3808 12.5003 10.0001C12.5003 8.61937 11.381 7.50008 10.0003 7.50008C8.61962 7.50008 7.50034 8.61937 7.50034 10.0001C7.50034 11.3808 8.61962 12.5001 10.0003 12.5001Z"
                  stroke="white"
                  stroke-width="1.3"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
    </div>

    <!--Footer-->
    <footer class="sm:pt-18.5">
        <Footer />
    </footer>
  </section>
</template>

<script>
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";
import { useRoute } from "vue-router";


const route = useRoute();

</script>
