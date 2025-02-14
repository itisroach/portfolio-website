<script>
import projects from '/src/projects.json'

export default {
  data() {
    return {
      projects: projects,
    };
  },
};
</script>
<template>
    <section class="flex flex-col justify-center items-center lg:gap-10 gap-5">
        <h1 data-aos="fade-up" data-aos-duration="2000" class="lg:text-4xl text-2xl font-semibold">
            Projects
        </h1>
        <div class="grid grid-cols-2 lg:gap-10 gap-4">
            <div v-for="(project, idx) in projects" class="flex flex-col from-blue-700 to-gray-700 bg-gradient-to-br relative text-white lg:px-10 px-3 lg:py-5 py-2 rounded-xl" :data-aos="idx % 2 == 0 ? 'fade-right' : 'fade-left'" data-aos-duration="2000">
                <p class="lg:text-3xl text-xl font-semibold">{{ project.title }}</p>
                <p class="lg:text-lg break-all text-justify my-2 text-xs">{{ project.description }}</p>
                <div class="flex flex-wrap lg:gap-3 gap-0.5 mb-8 mt-auto">
                    <p v-for="tech in project.techs" class="bg-gray-700 lg:text-base text-xs lg:px-4 px-2 py-2 rounded-xl text-center">
                        {{ tech }}
                    </p>
                </div>
                <div class="absolute bottom-2 lg:left-10 left-4 grid grid-cols-2 gap-4">
                    <a target="_blank" v-if="project.link" blank="_" :href="project.link" title="View Live">
                        <svg xmlns="http://www.w3.org/2000/svg" class="lg:w-6 lg:h-6 w-5 h-5" viewBox="0 0 576 512"><path fill="#ffffff" d="M288 32c-80.8 0-145.5 36.8-192.6 80.6C48.6 156 17.3 208 2.5 243.7c-3.3 7.9-3.3 16.7 0 24.6C17.3 304 48.6 356 95.4 399.4C142.5 443.2 207.2 480 288 480s145.5-36.8 192.6-80.6c46.8-43.5 78.1-95.4 93-131.1c3.3-7.9 3.3-16.7 0-24.6c-14.9-35.7-46.2-87.7-93-131.1C433.5 68.8 368.8 32 288 32zM144 256a144 144 0 1 1 288 0 144 144 0 1 1 -288 0zm144-64c0 35.3-28.7 64-64 64c-7.1 0-13.9-1.2-20.3-3.3c-5.5-1.8-11.9 1.6-11.7 7.4c.3 6.9 1.3 13.8 3.2 20.7c13.7 51.2 66.4 81.6 117.6 67.9s81.6-66.4 67.9-117.6c-11.1-41.5-47.8-69.4-88.6-71.1c-5.8-.2-9.2 6.1-7.4 11.7c2.1 6.4 3.3 13.2 3.3 20.3z"/></svg>
                    </a>
                    <a target="_blank" :href="project.repo">
                        <svg xmlns="http://www.w3.org/2000/svg" class="lg:w-6 lg:h-6 w-5 h-5" x="0px" y="0px" width="30" height="30" viewBox="0 0 30 30"
                        style="fill:#FFFFFF;">
                            <path d="M15,3C8.373,3,3,8.373,3,15c0,5.623,3.872,10.328,9.092,11.63C12.036,26.468,12,26.28,12,26.047v-2.051 c-0.487,0-1.303,0-1.508,0c-0.821,0-1.551-0.353-1.905-1.009c-0.393-0.729-0.461-1.844-1.435-2.526 c-0.289-0.227-0.069-0.486,0.264-0.451c0.615,0.174,1.125,0.596,1.605,1.222c0.478,0.627,0.703,0.769,1.596,0.769 c0.433,0,1.081-0.025,1.691-0.121c0.328-0.833,0.895-1.6,1.588-1.962c-3.996-0.411-5.903-2.399-5.903-5.098 c0-1.162,0.495-2.286,1.336-3.233C9.053,10.647,8.706,8.73,9.435,8c1.798,0,2.885,1.166,3.146,1.481C13.477,9.174,14.461,9,15.495,9 c1.036,0,2.024,0.174,2.922,0.483C18.675,9.17,19.763,8,21.565,8c0.732,0.731,0.381,2.656,0.102,3.594 c0.836,0.945,1.328,2.066,1.328,3.226c0,2.697-1.904,4.684-5.894,5.097C18.199,20.49,19,22.1,19,23.313v2.734 c0,0.104-0.023,0.179-0.035,0.268C23.641,24.676,27,20.236,27,15C27,8.373,21.627,3,15,3z"></path>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </section>
</template>


