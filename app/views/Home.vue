<template>
  <div>
    <Header />
    <Hero />
    <About />
    <Projects />
    <Skills />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import About from '@/components/About.vue';
import Projects from '@/components/Projects.vue';
import Skills from '@/components/Skills.vue';
import Contact from '@/components/Contact.vue';
import Footer from '@/components/Footer.vue';

export default {
  components: {
    Header,
    Hero,
    About,
    Projects,
    Skills,
    Contact,
    Footer
  }
}
</script>

<style scoped>
/* Add any specific styles for the Home view here */
</style>