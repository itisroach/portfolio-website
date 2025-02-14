<script setup>
import HeaderComp from './components/HeaderComp.vue';
import Skills from './components/Skills.vue';
import Projects from './components/Projects.vue';
import Footer from './components/Footer.vue';
import AOS from 'aos';
import 'aos/dist/aos.css';
import Resume from '../public/files/Resume.pdf'
AOS.init();

</script>

<template>
  <a :href="Resume" download class="fixed z-60 bg-slate-700 opacity-45 focus:opacity-100 hover:opacity-100 transition-all py-2 px-4 rounded-lg right-2 lg:right-2 lg:text-sm  top-2 text-white text-xs">Download My Resume</a>
  <section id="main"> 
    <HeaderComp data-aos="fade-right" data-aos-duration="2000" />
    <Skills data-aos="fade-left" data-aos-duration="2000" />
  </section>
  <div class="lg:mt-72 mt-60 flex justify-center items-center  relative">
    <svg class="pointer" xmlns="http://www.w3.org/2000/svg" width="30" viewBox="0 0 320 512"><path fill="#ffffff" d="M137.4 374.6c12.5 12.5 32.8 12.5 45.3 0l128-128c9.2-9.2 11.9-22.9 6.9-34.9s-16.6-19.8-29.6-19.8L32 192c-12.9 0-24.6 7.8-29.6 19.8s-2.2 25.7 6.9 34.9l128 128z"/></svg>
  </div>
  <Projects />
  <div class="border border-b-0 mt-10 border-gray-500"></div>
  <Footer  data-aos="fade-up" data-aos-duration="2000"  />
</template>


