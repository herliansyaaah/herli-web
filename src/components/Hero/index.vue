<template>
  <div class="hero relative isolate w-full relative -mt-20 flex items-center justify-center h-screen">
    <div class="absolute inset-x-0 -top-40 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80" aria-hidden="true">
      <div class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%-30rem)] sm:w-[72.1875rem]" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
    </div>
    <div>
      <img class="sparkle-top absolute animate-spin" src="../../assets/sparkle.png">
    </div>
    <div class="z-10 text-center px-4" data-aos="fade-up" >
      <div class="flex justify-center font-bold md:text-7xl text-4xl">
        <p>Hi, I’m Herli </p>
        <p class="animate-waving">👋</p>
      </div>
      <h1 class="gradient-text font-bold md:text-7xl text-4xl md:my-4 mt-2 md:pb-3">
        A Happy Fullstack Developer
      </h1>
      <div class="text-md md:text-2xl text-gray-600 md:mt-7 mt-2 mb-5">
        <p class="font-bold"> 1+ years of experience in Fullstack Development,</p>
        using Javascript framework and Laravel for developing a web applications.
      </div>
      <a href="#profile">
        <button
          class="btn-scroll animate-bounce mt-5 text-gray-400 border border-gray-300 rounded-full 
          bg-white bg-opacity-30 shadow-md hover:border-blue-500 hover:text-blue-500 md:px-3 md:py-2 px-3 py-1.5">
          <font-awesome-icon :icon="['fas', 'arrow-down']" beat-fade class="mr-0.5 md:mr-2" />
          Scroll Down
        </button>
      </a>
      <div>
        <img class="sparkle-bottom absolute animate-pulse" src="../../assets/sparkle.png">
      </div>
    </div>
  </div>
</template>
