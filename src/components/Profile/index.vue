<template>
  <section class="profile py-10 md:py-5" id="profile">
    <div class="grid z-10 grid-cols-12 gap-2 container md:mx-auto px-5">
      <div class="col-span-8 items-center justify-center">
        <div class="md:text-4xl text-2xl flex font-bold" data-aos="fade-right">
          <p>👨‍💻</p>
          <p class="gradient-text ml-2" >About me</p>
        </div>
      </div>
      <div data-aos="zoom-in" class="justify-self-end col-span-4">
        <div class="border flex rounded-full text:sm gradient-blue text-white px-3 py-1.5 md:hidden">
          <font-awesome-icon :icon="['fas', 'download']" class="mr-2"/>
          <p class="text-sm">Resume</p> </div>
      </div>
      <div class="col-span-12 mt-2 md:col-span-6 md:mt-4 text-gray-600" data-aos="fade-up">
        <p class="text-md text-sky-500 md:text-lg mb-2 md:mb-2">
          <font-awesome-icon :icon="['fas', 'circle']" fade /> Available for hire </p>
        <p class="text-md md:text-xl mb-4 md:mb-6">
            I'm an experienced web developer, specializing in JavaScript frameworks. 
            Highly interested in building huge userbase applications using 
            any web technology. I'm enthusiastic to learn new things and 
            passionate to share things that I had explored with others.
        </p>
        <!-- <p class="text-md md:text-xl mb-4 md:mb-6">
            Wishing to use strong analytical, aesthetic, 
            and problem-solving skills to improve user experience 
            and optimize application performance.
        </p> -->
        <div class="flex gap-2">
          <a href="https://www.linkedin.com/in/suherli-sutansyach/" class="border  rounded-full bg-white p-2 bg-gradient-to-r from-cyan-500 to-blue-500">
            <font-awesome-icon :icon="['fab', 'linkedin']" size="xl" class="text-white"/>
          </a>
          <a href="https://github.com/herliansyaaah" class="border rounded-full p-2 bg-gradient-to-r from-violet-500 to-fuchsia-500">
            <font-awesome-icon :icon="['fab', 'github']" size="xl" class="text-white"/>
          </a>
          <a href="https://www.instagram.com/herlipotter" class="border rounded-full bg-gradient-to-r from-pink-500 to-red-400 p-2">
            <font-awesome-icon :icon="['fab', 'instagram']" size="xl" class="text-white"/>
          </a>
          <a href="https://www.medium.com/@suherlisutansyach" class="border rounded-full bg-gradient-to-r from-gray-500 to-black p-2">
            <font-awesome-icon :icon="['fab', 'medium']" size="lg" class="text-white"/>
          </a>
          <a href="https://www.behance.com/herliansyaaah" class="border rounded-full bg-gradient-to-r from-blue-600 to-cyan-600 p-2">
            <font-awesome-icon :icon="['fab', 'behance']" size="lg" class="text-white"/>
          </a>
        </div>
        <button class="btn-download mt-4 md:mt-8 gradient-blue text-white border rounded-full px-4 py-3 hidden md:block">
          <font-awesome-icon :icon="['fas', 'download']" class="mr-2" />
           Download Resume
        </button>
      </div>
      <div class="col-span-12 mt-2 md:col-span-6 md:mt-4 text-gray-600 flex items-center justify-center md:-mt-24">
        <div class="shape absolute mx-4 isolate hidden md:block">
          <div class="bg-shape1 blur-3xl"></div>
          <div class="bg-shape2 blur-3xl"></div>
        </div>
        <div class="image-avatar hidden md:block md:mb-10" data-aos="fade-left">
          <img src="../../assets/avatar.png">
        </div>
      </div>  
    </div>
  </section>
</template>