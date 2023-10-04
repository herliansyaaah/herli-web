<template>
  <nav class="sticky top-2 flex py-2 px-2 justify-center relative z-50">
    <div class="backdrop-blur-sm flex justify-center bg-white bg-opacity-30 shadow-md md:px-3 md:py-3 px-2 py-1.5 rounded-full border">
      <div class="flex flex-1">
        <div class="sm:ml-0 sm:block ">
          <div class="flex gap-x-1 md:gap-x-2">
            <a href="#profile" class="nav-link hover:text-black hover:bg-gray-200 text-gray-700 rounded-full md:px-4 md:py-2 py-2 px-2 text-sm font-medium">Profile</a>
            <a href="#experience" class="nav-link text-gray-700 hover:text-black hover:bg-gray-200 rounded-full md:px-4 md:py-2 py-2 px-2 text-sm font-medium">Experience</a>
            <a href="#project" class="nav-link text-gray-700 hover:text-black hover:bg-gray-200 rounded-full md:px-4 md:py-2 py-2 px-2 text-sm font-medium">Project</a>
            <a href="#contact" class="nav-link text-gray-700 hover:text-black hover:bg-gray-200 rounded-full md:px-4 md:py-2 py-2 px-2 text-sm font-medium">Contact</a>
            <div class="animation start-home"></div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  mounted() {
    window.addEventListener('scroll', this.setActiveNavLink);
  },
  methods: {
    setActiveNavLink() {
      let currentSectionId = null;
      for (const sectionId of ['profile', 'experience', 'project', 'contact']) {
        const section = document.getElementById(sectionId);
        if (!section) continue;

        const rect = section.getBoundingClientRect();

        if (rect.top >= 0 && rect.top <= window.innerHeight * 0.6) {
          currentSectionId = sectionId;
          break;
        }
      }
      const navLinks = document.querySelectorAll('.nav-link');
      navLinks.forEach(link => {
        link.classList.remove('active');
      });
      if (currentSectionId) {
        const activeLink = document.querySelector(`.nav-link[href="#${currentSectionId}"]`);
        if (activeLink) {
          activeLink.classList.add('active');
        }
      }
    },
  },
  beforeDestroy() {
    window.removeEventListener('scroll', this.setActiveNavLink);
  },
};
</script>


