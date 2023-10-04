<template>
  <div class="project relative isolate py-10 h-full" id="project">
    <div class="background-blur absolute inset-x-0 -top-40 transform-gpu overflow-hidden blur-3xl sm:-top-80"
      aria-hidden="true">
      <div class="relative left-[calc(25%+4rem)] 
      aspect-[1155/678] w-[36.125rem] 
      -translate-x-1/2 rotate-[30deg] 
      bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 
      sm:left-[calc(50%+20rem)] sm:w-[72.1875rem]"
        style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)">
      </div>
    </div>
    <div class="grid grid-cols-12 container md:mx-auto px-5">
      <div class="col-span-12 flex" data-aos="fade-right">
        <h2 class="text-2xl md:text-3xl font-bold">
          🚀
        </h2>
        <h2 class="gradient-text text-2xl md:text-4xl font-bold ml-2">
          Latest Project
        </h2>
      </div>
      <div class="col-span-12 md:col-span-7 mt-4" data-aos="fade-up">
        <h2 class="text-xl md:text-2xl font-semibold">
          I knew to be done is good, but sharing our experiences and it “works” is
          way better
        </h2>
      </div>
      <div class="col-span-12 md:col-span-6 mt-2" data-aos="fade-up">
        <p class="text-md md:text-xl mb-4">
          These are some of the projects I have created.
          These projects have not only helped me build my
          portfolio, but also enhanced the skills I have developed.
        </p>
      </div>
    </div>


    <div class="grid grid-cols-1 lg:grid-cols-3 gap-4 container md:mx-auto px-5">
      <div class="bg-white border border-gray-200 hover:border-cyan-500 rounded-lg shadow" data-aos="fade-up">
        <div class="relative">
          <img class="rounded-t-lg opacity-100 hover:opacity-25" 
          src="../../assets/personal-web.jpg"/>
          <div class="absolute hover-img inset-0 gap-x-1 flex items-center justify-center opacity-0 hover:opacity-75 transition-opacity duration-300">
            <button @click="openURL(githubUrl.personalWeb)" class="bg-blue-500 text-white py-2 px-3 rounded-full">
              <font-awesome-icon :icon="['fas', 'code']" />
            </button>
            <button @click="openURL(website.personalWeb)" class="bg-blue-500 text-white py-2 px-3 rounded-full">
              <font-awesome-icon :icon="['fas', 'eye']" />
            </button>
          </div>
        </div>
        <div class="px-5 py-3">
          <h5 class="mb-4 text-lg md:text-xl font-semibold tracking-tight text-black">
            Herlipotter.com</h5>
          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            This personal website built with Vue.js for the frontend and Laravel for the backend. </p>
          <div class="icon flex gap-x-4 mt-4">
            <font-awesome-icon class="text-green-700" :icon="['fab', 'vuejs']" size="xl" title="Vue JS" />
            <font-awesome-icon class="text-pink-700" :icon="['fab', 'laravel']" size="xl" title="Laravel" />
            <svg alt="Vite" width="24px" height="24px" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg" fill="none">
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
              <g id="SVGRepo_iconCarrier">
                <title>Vite</title>
                <path
                  d="M29.8836 6.146L16.7418 29.6457c-.2714.4851-.9684.488-1.2439.0052L2.0956 6.1482c-.3-.5262.1498-1.1635.746-1.057l13.156 2.3516a.7144.7144 0 00.2537-.0004l12.8808-2.3478c.5942-.1083 1.0463.5241.7515 1.0513z"
                  fill="url(#paint0_linear)"></path>
                <path
                  d="M22.2644 2.0069l-9.7253 1.9056a.3571.3571 0 00-.2879.3294l-.5982 10.1038c-.014.238.2045.4227.4367.3691l2.7077-.6248c.2534-.0585.4823.1647.4302.4194l-.8044 3.9393c-.0542.265.1947.4918.4536.4132l1.6724-.5082c.2593-.0787.5084.1487.4536.414l-1.2784 6.1877c-.08.387.4348.598.6495.2662L16.5173 25 24.442 9.1848c.1327-.2648-.096-.5667-.387-.5106l-2.787.5379c-.262.0505-.4848-.1934-.4109-.4497l1.8191-6.306c.074-.2568-.1496-.5009-.4118-.4495z"
                  fill="url(#paint1_linear)"></path>
                <defs id="defs50">
                  <linearGradient id="paint0_linear" x1="6.0002" y1="32.9999" x2="235" y2="344"
                    gradientUnits="userSpaceOnUse" gradientTransform="matrix(.07142 0 0 .07142 1.3398 1.8944)">
                    <stop stop-color="#41D1FF" id="stop38"></stop>
                    <stop offset="1" stop-color="#BD34FE" id="stop40"></stop>
                  </linearGradient>
                  <linearGradient id="paint1_linear" x1="194.651" y1="8.8182" x2="236.076" y2="292.989"
                    gradientUnits="userSpaceOnUse" gradientTransform="matrix(.07142 0 0 .07142 1.3398 1.8944)">
                    <stop stop-color="#FFEA83" id="stop43"></stop>
                    <stop offset=".0833" stop-color="#FFDD35" id="stop45"></stop>
                    <stop offset="1" stop-color="#FFA800" id="stop47"></stop>
                  </linearGradient>
                </defs>
              </g>
            </svg>
            <svg class="-ml-5 -mt-1" fill="#4d74ea" width="64px" height="34px" viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg" xml:space="preserve" stroke="#4d74ea">
              <g id="SVGRepo_bgCarrier" stroke-width="0">
              </g>
              <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round" stroke="#CCCCCC"
                stroke-width="0.048"></g>
              <g id="SVGRepo_iconCarrier">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M12 6.036c-2.667 0-4.333 1.325-5 3.976 
                  1-1.325 2.167-1.822 3.5-1.491.761.189 1.305.738 1.906 
                  1.345C13.387 10.855 14.522 12 17 12c2.667 0 4.333-1.325 
                  5-3.976-1 1.325-2.166 1.822-3.5 
                  1.491-.761-.189-1.305-.738-1.907-1.345-.98-.99-2.114-2.134-4.593-2.134zM7 
                  12c-2.667 0-4.333 1.325-5 3.976 1-1.326 2.167-1.822 3.5-1.491.761.189 
                  1.305.738 1.907 1.345.98.989 2.115 2.134 4.594 2.134 2.667 
                  0 4.333-1.325 5-3.976-1 1.325-2.167 1.822-3.5 1.491-.761-.189-1.305-.738-1.906-1.345C10.613 
                  13.145 9.478 12 7 12z">
                </path>
              </g>
            </svg>
          </div>
        </div>
      </div>

      <div class="bg-white border border-gray-200 hover:border-cyan-500 rounded-lg shadow" data-aos="fade-up">
        <div class="relative">
          <img class="rounded-t-lg opacity-100 hover:opacity-25" 
          src="../../assets/spk.jpg"/>
          <div class="absolute hover-img inset-0 gap-x-1 flex items-center justify-center opacity-0 hover:opacity-75 transition-opacity duration-300">
            <button @click="openURL(githubUrl.spk)" class="bg-blue-500 text-white py-2 px-3 rounded-full">
              <font-awesome-icon :icon="['fas', 'code']" />
            </button>
            <button @click="openURL(website.personalWeb)" class="bg-blue-500 text-white py-2 px-3 rounded-full">
              <font-awesome-icon :icon="['fas', 'eye']" />
            </button>
          </div>
        </div>
        <div class="px-5 py-3">
          <h5 class="mb-4 text-lg md:text-xl font-semibold tracking-tight text-black">
            Decision Support Systems</h5>
          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            This Decision Support System was created to assist the HR department in determining employee bonuses utilizes
            the AHP and SAW methods.
          </p>
          <div class="flex gap-x-4 mt-4">
            <font-awesome-icon class="text-red-600" :icon="['fab', 'html5']" size="xl" title="HTML" />
            <font-awesome-icon class="text-blue-700" :icon="['fab', 'css3-alt']" size="xl" title="CSS" />
            <font-awesome-icon class="text-purple-500" :icon="['fab', 'php']" size="xl" title="PHP" />
            <svg fill="#ff4d4d" width="22px" height="22px" viewBox="0 0 32 32" version="1.1"
              xmlns="http://www.w3.org/2000/svg" stroke="#ff4d4d">
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
              <g id="SVGRepo_iconCarrier">
                <title>codeigniter</title>
                <path
                  d="M15.333 1.004c1.1 1.778-0.35 4.131-1.508 5.446-1.123 1.275-2.489 2.341-3.73 3.499-1.344 1.223-2.559 2.536-3.655 3.945l-0.052 0.070c-1.75 2.074-2.814 4.776-2.814 7.727 0 0.892 0.097 1.762 0.282 2.599l-0.015-0.080c1.123 3.498 4.043 6.111 7.646 6.775l0.061 0.009c-1.922-0.827-3.285-2.62-3.485-4.751l-0.002-0.023c0.13-2.236 1.336-4.165 3.103-5.29l0.027-0.016c-0.117 0.273-0.185 0.59-0.185 0.923 0 0.48 0.141 0.928 0.384 1.303l-0.006-0.009c0.381 0.518 0.988 0.85 1.673 0.85 1.143 0 2.070-0.927 2.070-2.070 0-0.654-0.303-1.237-0.777-1.616l-0.004-0.003c-1.079-0.86-1.765-2.174-1.765-3.648 0-0.202 0.013-0.401 0.038-0.596l-0.002 0.023c0.241-0.898 0.733-1.66 1.395-2.228l0.006-0.005c-0.512 1.347 0.943 2.674 1.903 3.337 1.937 1.142 3.575 2.251 5.142 3.449l-0.123-0.090c1.567 1.206 2.567 3.083 2.567 5.194 0 0.123-0.003 0.244-0.010 0.365l0.001-0.017c-0.42 2.337-2.083 4.202-4.267 4.906l-0.045 0.012c4.526-1 9.204-4.511 9.297-9.531 0.116-3.789-2.378-7.144-6.446-9.227 0.081 0.15 0.129 0.329 0.129 0.518 0 0.238-0.075 0.459-0.204 0.64l0.002-0.003c-0.397 0.616-1.079 1.018-1.856 1.018-0.676 0-1.281-0.305-1.684-0.785l-0.003-0.003c-1.506-1.934 0.031-4.019 0.246-6.067 0.002-0.068 0.003-0.147 0.003-0.227 0-2.616-1.312-4.926-3.314-6.307l-0.026-0.017z">
                </path>
              </g>
            </svg>
          </div>
        </div>
      </div>

      <div class=" bg-white border border-gray-200 hover:border-cyan-500 rounded-lg shadow" data-aos="fade-up">
        <div class="relative">
          <img class="rounded-t-lg opacity-100 hover:opacity-25" 
          src="../../assets/holy-quran.jpg"/>
          <div class="absolute hover-img inset-0 gap-x-1 flex items-center justify-center opacity-0 hover:opacity-75 transition-opacity duration-300">
            <button @click="openURL(githubUrl.holyQuran)" class="bg-blue-500 text-white py-2 px-3 rounded-full">
              <font-awesome-icon :icon="['fas', 'code']" />
            </button>
            <button @click="openURL(website.holyQuran)" class="bg-blue-500 text-white py-2 px-3 rounded-full">
              <font-awesome-icon :icon="['fas', 'eye']" />
            </button>
          </div>
        </div>
        <div class="px-5 py-3">
          <h5 class="mb-4 text-lg md:text-xl font-semibold tracking-tight text-black">
            Holy Qur'an </h5>
          <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
            This website aims to facilitate reading, studying,
            and understanding the Al-Quran for everyone.</p>
          <div class="flex gap-x-4 mt-4">
            <font-awesome-icon class="text-green-700" :icon="['fab', 'vuejs']" size="xl" title="Vue JS" />
            <font-awesome-icon class="text-purple-800" :icon="['fab', 'bootstrap']" size="xl" title="Bootstrap" />
            <svg alt="Vite" width="24px" height="24px" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg" fill="none">
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
              <g id="SVGRepo_iconCarrier">
                <title>Vite</title>
                <path
                  d="M29.8836 6.146L16.7418 29.6457c-.2714.4851-.9684.488-1.2439.0052L2.0956 6.1482c-.3-.5262.1498-1.1635.746-1.057l13.156 2.3516a.7144.7144 0 00.2537-.0004l12.8808-2.3478c.5942-.1083 1.0463.5241.7515 1.0513z"
                  fill="url(#paint0_linear)"></path>
                <path
                  d="M22.2644 2.0069l-9.7253 1.9056a.3571.3571 0 00-.2879.3294l-.5982 10.1038c-.014.238.2045.4227.4367.3691l2.7077-.6248c.2534-.0585.4823.1647.4302.4194l-.8044 3.9393c-.0542.265.1947.4918.4536.4132l1.6724-.5082c.2593-.0787.5084.1487.4536.414l-1.2784 6.1877c-.08.387.4348.598.6495.2662L16.5173 25 24.442 9.1848c.1327-.2648-.096-.5667-.387-.5106l-2.787.5379c-.262.0505-.4848-.1934-.4109-.4497l1.8191-6.306c.074-.2568-.1496-.5009-.4118-.4495z"
                  fill="url(#paint1_linear)"></path>
                <defs id="defs50">
                  <linearGradient id="paint0_linear" x1="6.0002" y1="32.9999" x2="235" y2="344"
                    gradientUnits="userSpaceOnUse" gradientTransform="matrix(.07142 0 0 .07142 1.3398 1.8944)">
                    <stop stop-color="#41D1FF" id="stop38"></stop>
                    <stop offset="1" stop-color="#BD34FE" id="stop40"></stop>
                  </linearGradient>
                  <linearGradient id="paint1_linear" x1="194.651" y1="8.8182" x2="236.076" y2="292.989"
                    gradientUnits="userSpaceOnUse" gradientTransform="matrix(.07142 0 0 .07142 1.3398 1.8944)">
                    <stop stop-color="#FFEA83" id="stop43">
                    </stop>
                    <stop offset=".0833" stop-color="#FFDD35" id="stop45">
                    </stop>
                    <stop offset="1" stop-color="#FFA800" id="stop47"></stop>
                  </linearGradient>
                </defs>
              </g>
            </svg>
          </div>
        </div>
      </div>

      <div class="bg-white border border-gray-200 hover:border-cyan-500 rounded-lg shadow" data-aos="fade-up">
        <div class="relative">
          <img class="rounded-t-lg border hover:border-cyan-500 opacity-100 hover:opacity-25" 
          src="../../assets/devhub.jpg"/>
          <div class="absolute hover-img inset-0 flex flex-col items-center text-center justify-center opacity-0 hover:opacity-75 transition-opacity duration-300 px-4">
            <small class=" text-white mb-2 border rounded-full py-1.5 px-2 border-white"><font-awesome-icon icon="fa-solid fa-eye-slash"/> Private Content</small>
            <small class="text-white">Can't show code and preview because this project is private property of PT Parkland World Indonesia</small>
          </div>
        </div>
        <div class="px-5 py-3">
          <h5 class="mb-4 text-lg md:text-xl font-semibold tracking-tight text-black">
            Development Hub - DevHub
          </h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
          A system for the shoe development & production, can integrate various major departments and serves 
          as a data warehouse to centralize all departmental data. 
          It also provides dashboards and reports for each team.</p>
        <div class="tech flex gap-x-4 mt-4" style="order: 1;">
          <font-awesome-icon class="text-green-700" :icon="['fab', 'vuejs']" size="xl" title="Vue JS" />
          <font-awesome-icon class="text-pink-700" :icon="['fab', 'laravel']" size="xl" title="Laravel" />
          <font-awesome-icon class="text-purple-800" :icon="['fab', 'bootstrap']" size="xl" title="Bootstrap" />
        </div>
      </div>
    </div>

    <!-- <div class=" bg-white border border-gray-200 hover:border-cyan-500 rounded-lg shadow" data-aos="fade-up">
      <a href="#">
        <img class="rounded-t-lg border" src="../../assets/personal-web.jpg" alt="" />
      </a>
      <div class="px-5 py-3">
        <a href="#">
          <h5 class="mb-4 text-lg md:text-xl font-semibold tracking-tight text-black">
            Quality Inspection Systems</h5>
        </a>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">
          Quality inspection system designed to track and record defects in shoe manufacturing process</p>
        <div class="tech flex gap-x-4 mt-4" style="order: 1;">
          <font-awesome-icon class="text-green-700" :icon="['fab', 'vuejs']" size="xl" title="Vue JS" />
          <font-awesome-icon class="text-pink-700" :icon="['fab', 'laravel']" size="xl" title="Laravel" />
          <svg class="-ml-5 -mt-1" fill="#4d74ea" width="64px" height="34px" viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg" xml:space="preserve" stroke="#4d74ea">
            <g id="SVGRepo_bgCarrier" stroke-width="0">
            </g>
            <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round" stroke="#CCCCCC"
              stroke-width="0.048"></g>
            <g id="SVGRepo_iconCarrier">
              <path fill-rule="evenodd" clip-rule="evenodd" d="M12 6.036c-2.667 0-4.333 1.325-5 3.976 
                  1-1.325 2.167-1.822 3.5-1.491.761.189 1.305.738 1.906 
                  1.345C13.387 10.855 14.522 12 17 12c2.667 0 4.333-1.325 
                  5-3.976-1 1.325-2.166 1.822-3.5 
                  1.491-.761-.189-1.305-.738-1.907-1.345-.98-.99-2.114-2.134-4.593-2.134zM7 
                  12c-2.667 0-4.333 1.325-5 3.976 1-1.326 2.167-1.822 3.5-1.491.761.189 
                  1.305.738 1.907 1.345.98.989 2.115 2.134 4.594 2.134 2.667 
                  0 4.333-1.325 5-3.976-1 1.325-2.167 1.822-3.5 1.491-.761-.189-1.305-.738-1.906-1.345C10.613 
                  13.145 9.478 12 7 12z">
              </path>
            </g>
          </svg>
        </div>
      </div>
    </div> -->
  </div>
</div>
</template>

<script>
export default {
  data(){
    return{
      website:{
        personalWeb:'https://herlipotter.com/',
        holyQuran:'https://holy.herlipotter.com/',
      },
      githubUrl:{
        personalWeb:"https://github.com/herliansyaaah/herli-web/",
        holyQuran:"https://github.com/herliansyaaah/holy-quran/",
        spk:"https://github.com/herliansyaaah/SPK-AHP-SAW/",
      }
    }
  },
  methods: {
    openURL(url) {
      window.open(url, '_blank');
    },
  },
};
</script>

