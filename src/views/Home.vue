<template>
  <Hero />
  <About />
  <Work />
  <Skills />
  <Project />
  <Contact />
  <Footer />
  
</template>

<script>
import Hero from '../components/Hero/index.vue'
import About from '../components/Profile/index.vue'
import Work from '../components/Experience/index.vue'
import Skills from '../components/Skills/index.vue'
import Project from '../components/Portofolio/index.vue'
import Contact from '../components/Contact/index.vue'
import Footer from '../components/Footer/index.vue'

export default {
  components: {
    Hero,
    About,
    Work,
    Skills,
    Project,
    Contact,
    Footer,
  },
  data() {
    return {
    }
  },
}
</script>
