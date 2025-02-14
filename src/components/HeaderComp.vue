<template>
    <header class="flex flex-col justify-center items-center">
        <div class="flex flex-col lg:gap-1 gap-0.5">
            <div class="lg:text-4xl text-2xl font-semibold flex lg:gap-1 gap-0.5 lg:mt-2 mt-0.5 from-gray-500 to-blue-500 bg-gradient-to-r bg-clip-text text-transparent">
                <p>Hi I'm Amirali Ashoori </p>
                <img class="lg:w-14 w-8" src="https://raw.githubusercontent.com/hjemmel/hjemmel/master/images/wave.gif" alt="">
            </div>
            <p class="text-grey-400 opacity-70 lg:text-xl text-base">
                Back-End Developer
            </p>
            <p class="text-justify lg:text-base text-xs">
                I’m a back-end developer who loves to code and make new things. I’ve built some open-sourced projects with back-end 
                technologies like Golang, Django and NodeJs that you can see on my GitHub account. Feel free to share 
                your thoughts about my projects. I’m looking forward to joining a professional team with a positive 
                environment which we can share our knowledge and learn from each other while enjoy working.
            </p>
            <ul class="flex pt-2 lg:mt-2 lg:pt-4 justify-start items-center w-fit rounded-3xl">
                <li class="hover:opacity-60 focus:opacity-60 lg:pr-4 lg:py-1 rounded-xl transition-all">
                    <a target="_blank" href="https://github.com/itisroach" class="flex flex-col justify-center items-center lg:gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" class="lg:w-8 w-6" viewBox="0 0 30 30"
                        style="fill:#FFFFFF;">
                            <path d="M15,3C8.373,3,3,8.373,3,15c0,5.623,3.872,10.328,9.092,11.63C12.036,26.468,12,26.28,12,26.047v-2.051 c-0.487,0-1.303,0-1.508,0c-0.821,0-1.551-0.353-1.905-1.009c-0.393-0.729-0.461-1.844-1.435-2.526 c-0.289-0.227-0.069-0.486,0.264-0.451c0.615,0.174,1.125,0.596,1.605,1.222c0.478,0.627,0.703,0.769,1.596,0.769 c0.433,0,1.081-0.025,1.691-0.121c0.328-0.833,0.895-1.6,1.588-1.962c-3.996-0.411-5.903-2.399-5.903-5.098 c0-1.162,0.495-2.286,1.336-3.233C9.053,10.647,8.706,8.73,9.435,8c1.798,0,2.885,1.166,3.146,1.481C13.477,9.174,14.461,9,15.495,9 c1.036,0,2.024,0.174,2.922,0.483C18.675,9.17,19.763,8,21.565,8c0.732,0.731,0.381,2.656,0.102,3.594 c0.836,0.945,1.328,2.066,1.328,3.226c0,2.697-1.904,4.684-5.894,5.097C18.199,20.49,19,22.1,19,23.313v2.734 c0,0.104-0.023,0.179-0.035,0.268C23.641,24.676,27,20.236,27,15C27,8.373,21.627,3,15,3z"></path>
                        </svg>
                        <p class="lg:text-sm text-xs">Github</p>
                    </a>
                </li>
                <li class="hover:opacity-60 px-4 py-1 rounded-xl transition-all">
                    <a target="_blank" href="https://linkedin.com/in/amirali-ashoori" class="flex flex-col justify-center items-center gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" class="lg:w-8 w-6" viewBox="0 0 50 50" style="fill:#FFFFFF;"> <path d="M41,4H9C6.24,4,4,6.24,4,9v32c0,2.76,2.24,5,5,5h32c2.76,0,5-2.24,5-5V9C46,6.24,43.76,4,41,4z M17,20v19h-6V20H17z M11,14.47c0-1.4,1.2-2.47,3-2.47s2.93,1.07,3,2.47c0,1.4-1.12,2.53-3,2.53C12.2,17,11,15.87,11,14.47z M39,39h-6c0,0,0-9.26,0-10 c0-2-1-4-3.5-4.04h-0.08C27,24.96,26,27.02,26,29c0,0.91,0,10,0,10h-6V20h6v2.56c0,0,1.93-2.56,5.81-2.56 c3.97,0,7.19,2.73,7.19,8.26V39z"></path> </svg>
                        <p class="lg:text-sm text-xs">Linkedin</p>
                    </a>
                </li>
                <li class="hover:opacity-60 px-4 py-1 rounded-xl transition-all">
                    <a target="_blank" href="mailto:rouchashoori@gmail.com" class="flex flex-col justify-center items-center lg:gap-1">
                        <img class="lg:w-8 w-6" src="../assets/icons/email.png" alt="">
                        <p class="lg:text-sm text-xs">Email</p>
                    </a>
                </li>
                <li class="hover:opacity-60 px-4 py-1 rounded-xl transition-all">
                    <a target="_blank" href="https://t.me/thisisroach" class="flex flex-col justify-center items-center lg:gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" class="lg:w-8 w-6" viewBox="0 0 50 50" style="fill:#FFFFFF;"> <path d="M25,2c12.703,0,23,10.297,23,23S37.703,48,25,48S2,37.703,2,25S12.297,2,25,2z M32.934,34.375 c0.423-1.298,2.405-14.234,2.65-16.783c0.074-0.772-0.17-1.285-0.648-1.514c-0.578-0.278-1.434-0.139-2.427,0.219 c-1.362,0.491-18.774,7.884-19.78,8.312c-0.954,0.405-1.856,0.847-1.856,1.487c0,0.45,0.267,0.703,1.003,0.966 c0.766,0.273,2.695,0.858,3.834,1.172c1.097,0.303,2.346,0.04,3.046-0.395c0.742-0.461,9.305-6.191,9.92-6.693 c0.614-0.502,1.104,0.141,0.602,0.644c-0.502,0.502-6.38,6.207-7.155,6.997c-0.941,0.959-0.273,1.953,0.358,2.351 c0.721,0.454,5.906,3.932,6.687,4.49c0.781,0.558,1.573,0.811,2.298,0.811C32.191,36.439,32.573,35.484,32.934,34.375z"></path> </svg>
                        <p class="lg:text-sm text-xs">Telegram</p>
                    </a>
                </li>
                <li class="hover:opacity-60 rounded-xl transition-all">
                    <a target="_blank" href="tel:+989140329711" class="flex flex-col justify-center items-center lg:gap-1">
                        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" class="lg:w-8 w-6" viewBox="0 0 50 50" style="fill:#FFFFFF;"> <path d="M 14 3.9902344 C 8.4886661 3.9902344 4 8.4789008 4 13.990234 L 4 35.990234 C 4 41.501568 8.4886661 45.990234 14 45.990234 L 36 45.990234 C 41.511334 45.990234 46 41.501568 46 35.990234 L 46 13.990234 C 46 8.4789008 41.511334 3.9902344 36 3.9902344 L 14 3.9902344 z M 18.005859 12.033203 C 18.633859 12.060203 19.210594 12.414031 19.558594 12.957031 C 19.954594 13.575031 20.569141 14.534156 21.369141 15.785156 C 22.099141 16.926156 22.150047 18.399844 21.498047 19.589844 L 20.033203 21.673828 C 19.637203 22.237828 19.558219 22.959703 19.824219 23.595703 C 20.238219 24.585703 21.040797 26.107203 22.466797 27.533203 C 23.892797 28.959203 25.414297 29.761781 26.404297 30.175781 C 27.040297 30.441781 27.762172 30.362797 28.326172 29.966797 L 30.410156 28.501953 C 31.600156 27.849953 33.073844 27.901859 34.214844 28.630859 C 35.465844 29.430859 36.424969 30.045406 37.042969 30.441406 C 37.585969 30.789406 37.939797 31.366141 37.966797 31.994141 C 38.120797 35.558141 35.359641 37.001953 34.556641 37.001953 C 34.000641 37.001953 27.316344 37.761656 19.777344 30.222656 C 12.238344 22.683656 12.998047 15.999359 12.998047 15.443359 C 12.998047 14.640359 14.441859 11.879203 18.005859 12.033203 z"></path> </svg>
                        <p class="lg:text-sm text-xs text-wrap">Phone Number</p>
                    </a>
                </li>
            </ul>
        </div>
    </header>
</template>