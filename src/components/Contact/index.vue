<template>
  <div class="experience py-10 relative isolate overflow-hidden" id="contact">
    <div class="background-blur absolute inset-x-0 top-40 transform-gpu overflow-hidden blur-3xl sm:-top-40" aria-hidden="true">
      <div class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] 
      -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] 
      opacity-30 sm:left-[calc(50%+30rem)] sm:w-[72.1875rem]" 
      style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
    </div>
    <div class="grid grid-cols-12 container md:mx-auto px-5">
      <div class="col-span-12 flex" data-aos="fade-right">
        <h2 class="text-2xl md:text-3xl font-bold">
          ☕
        </h2>
        <h2 class="gradient-text text-2xl md:text-3xl font-bold ml-2">
          Let's get connected!
        </h2>
      </div>
      <div class="col-span-12 md:col-span-8 mt-4" data-aos="fade-up">
        <h2 class="text-xl md:text-2xl font-semibold">
          Do you have any project ideas?
          or would you like to join for a coffee?
          Feel free to get in touch! 😉
        </h2>
        <p class="text-md md:text-xl my-4">
          I'm like a ball of energy, eager to sprinkle some
          magic on your projects! 🚀
        </p>
      </div>
    </div>

    <div class="grid md:grid-cols-12 container md:mx-auto px-5 z-1" 
      data-aos="zoom-in">
      <div class="px-2 md:col-span-6 rounded-xl border w-full">
        <ul  class="divide-y divide-gray-200 dark:divide-gray-700">
          <li class="py-2 sm:py-4">
            <div class="flex items-center space-x-4">
              <div class="flex-shrink-0">
                <img class="w-24 h-24 rounded-full gradient-blue"
                 src="../../assets/avatar.png"
                  alt="Neil image">
              </div>
              <div class="flex-1 min-w-0">
                <p
                  class="text-md md:text-xl font-bold text-gray-900">
                  Contact me on :
                </p>
                <a href="mailto:hi@herlipotter.com"
                  class="flex text-md md:text-lg font-normal text-gray-900">
                  <img class="w-5 mr-2" src="../../assets/mail.svg" >
                  hi@herlipotter.com
                </a>
                <a href="https://instagram.com/herlipotter"
                 class="text-md md:text-lg text-gray-900 truncate dark:text-gray-400">
                  <font-awesome-icon class="text-red-500" :icon="['fab', 'instagram']" size="lg" />
                  @herlipotter
                </a>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>