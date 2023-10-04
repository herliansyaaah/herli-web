<template>
  <div class="skills px-4 z-40 container md:mx-auto px-5 py-10">
    <div class="grid grid-cols-12">
      <div class="col-span-12 text-center py-5">
        <div class="flex justify-center text-2xl md:text-4xl font-bold" data-aos="fade-down">
          <p class="mr-2">🎯</p>
          <p class="gradient-text">Specialized Skills</p>
        </div>
        <p class="text-md sm:text-xl md:mt-6 mt-4" data-aos="fade-up">
          This is the technology I usually use for development
        </p>
      </div>
    </div>
    <div class="techstck grid grid-col-12" data-aos="zoom-in">
      <div class="col-span-12 flex flex-wrap justify-center">
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'node-js']" fade
            class="md:h-16 h-12 text-green-400" />
          <p class="font-semibold">Node JS</p>
        </div>
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'vuejs']" beat
            class="md:h-16 h-12 text-green-700" />
          <p class="font-semibold">Vue JS</p>
        </div>
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'react']" spin
            class="md:h-16 h-12 text-blue-400" />
          <p class="font-semibold">React JS</p>
        </div>
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'square-js']" bounce
            class="md:h-16 h-12 text-yellow-400" />
          <p class="font-semibold">Javascript</p>
        </div>
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'laravel']" fade
            class="md:h-16 h-12 text-pink-700" />
          <p class="font-semibold">Laravel</p>
        </div>
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'figma']" bounce
            class="md:h-16 h-12 text-gray-700" />
          <p class="font-semibold">Figma</p>
        </div>
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'css3-alt']" flip
            class="md:h-16 h-12 text-blue-700" />
          <p class="font-semibold">CSS</p>
        </div>
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'html5']" shake
            class="md:h-16 h-12 text-red-600" />
          <p class="font-semibold">HTML5</p>
        </div>
        <div class="text-center p-4">
          <font-awesome-icon :icon="['fab', 'python']" beat
            class="md:h-16 h-12 text-yellow-300"/>
          <p class="font-semibold">Python</p>
        </div>
      </div>
    </div>
  </div>
</template>