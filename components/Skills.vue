<template>
    <div>
        <section class="">
            <div class="mx-auto px-4 sm:px-6 lg:max-w-7xl lg:px-8">
                <div class="flex flex-col lg:flex-row justify-between gap-8 xl:gap-16">
                    <div class="lg:w-2/5 flex items-end">
                        <div class="relative">
                            <div class="relative w-38">
                                <img src="~/assets/img/Skills.png" alt="">
                            </div>
                            <div class="absolute left-72 top-64 transform rotate-[10deg] hidden xl:block">
                                <!-- <img src="assets/images/about/about-p-2.png" class="w-full " alt=""> -->
                            </div>
                            <div class="absolute top-52 right-40 ">
                                <!-- <img src="assets/images/about/ph-circle.png" class="w-full hidden xl:block" alt=""> -->
                            </div>
                        </div>
                    </div>
                    <div class="lg:w-3/5">
                        <!-- <h2 class="text-4xl leading-normal lg:text-[42px] lg:leading-snug text-black-100 font-bold mb-3">
                            Photographer's new Beauty of form.
                        </h2>
                        <p class="text-lg text-black-500">
                            Famous Photographer's Never-Before-Seen Collection of Vintage
                            Street Photos Unveiled in New Book, Hello there! My name is
                            Robert Elisc. It uses a dictionary of over 200 Latin words,
                            combined
                        </p> -->

                        <div class="skills-boxes mt-10 mb-10 grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
                            <div
                                class="skill-card bg-[#f9f9f9] flex flex-col items-center justify-center border border-white rounded-lg p-[20px] group hover:bg-[#0252CD] glass bg-none">
                                <div
                                    class="flex justify-center items-center shadow-[inset_0px_0px_5px_0px_rgba(0,49,200,0.1)] bg-white text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center text-[35px] mb-4 ease-in-out group-hover:bg-transparent">
                                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" role="img"
                                        viewBox="0 0 24 24" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg">
                                        <title></title>
                                        <path
                                            d="M13.4642 19.8295h8.9218c.2834 0 .5618-.0723.8072-.2098a1.5899 1.5899 0 0 0 .5908-.5732 1.5293 1.5293 0 0 0 .216-.783 1.529 1.529 0 0 0-.2167-.7828L17.7916 7.4142a1.5904 1.5904 0 0 0-.5907-.573 1.6524 1.6524 0 0 0-.807-.2099c-.2833 0-.5616.0724-.807.2098a1.5904 1.5904 0 0 0-.5907.5731L13.4642 9.99l-2.9954-5.0366a1.5913 1.5913 0 0 0-.591-.573 1.6533 1.6533 0 0 0-.8071-.2098c-.2834 0-.5617.0723-.8072.2097a1.5913 1.5913 0 0 0-.591.573L.2168 17.4808A1.5292 1.5292 0 0 0 0 18.2635c-.0001.2749.0744.545.216.783a1.59 1.59 0 0 0 .5908.5732c.2454.1375.5238.2098.8072.2098h5.6003c2.219 0 3.8554-.9454 4.9813-2.7899l2.7337-4.5922L16.3935 9.99l4.3944 7.382h-5.8586ZM7.123 17.3694l-3.9083-.0009 5.8586-9.8421 2.9232 4.921-1.9572 3.2892c-.7478 1.1967-1.5972 1.6328-2.9163 1.6328z">
                                        </path>
                                    </svg>
                                </div>
                                <p class="group-hover:text-white text-[16px] font-normal">Nuxt</p>
                            </div>
                            <div
                                class="skill-card bg-[#f9f9f9] flex flex-col items-center justify-center border border-white rounded-lg p-[20px] group hover:bg-[#0252CD] glass bg-none">
                                <div
                                    class="flex justify-center items-center shadow-[inset_0px_0px_5px_0px_rgba(0,49,200,0.1)] bg-white text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center mb-4 ease-in-out group-hover:bg-transparent">
                                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 448 512"
                                        height="35px" width="35px" xmlns="http://www.w3.org/2000/svg">
                                        <path
                                            d="M356.9 64.3H280l-56 88.6-48-88.6H0L224 448 448 64.3h-91.1zm-301.2 32h53.8L224 294.5 338.4 96.3h53.8L224 384.5 55.7 96.3z">
                                        </path>
                                    </svg>
                                </div>
                                <p class="group-hover:text-white text-[16px] font-normal">Vue</p>
                            </div>
                            <div
                                class="skill-card bg-[#f9f9f9] flex flex-col items-center justify-center border border-white rounded-lg p-[20px] group hover:bg-[#0252CD] glass bg-none">
                                <div
                                    class="flex justify-center items-center shadow-[inset_0px_0px_5px_0px_rgba(0,49,200,0.1)] bg-white text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center mb-4 ease-in-out group-hover:bg-transparent">
                                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512"
                                        height="35px" width="35px" xmlns="http://www.w3.org/2000/svg">
                                        <path
                                            d="M208 88.001h-80v212.498c0 52.58-18.032 67.261-49.412 67.261-14.705 0-27.948-2.521-38.25-6.063L32 423.904C46.7 428.966 69.259 432 86.907 432 158.955 432 208 398.129 208 301.02V88.001zM382.463 80C305.02 80 256 123.998 256 182.154c0 50.083 37.751 81.44 92.641 101.665 39.7 14.158 55.392 26.808 55.392 47.539 0 22.756-18.139 37.425-52.448 37.425-31.863 0-60.789-10.64-80.394-21.255v-.021L256 410.727c18.639 10.638 53.441 21.255 91.167 21.255C437.854 431.98 480 383.43 480 326.284c0-48.55-26.958-79.9-85.278-102.163-43.139-17.191-61.27-26.795-61.27-48.542 0-17.2 15.688-32.869 48.043-32.869 31.846 0 53.744 10.707 66.505 17.291l19.125-64C447.125 87.22 420.188 80 382.463 80z">
                                        </path>
                                    </svg>
                                </div>
                                <p class="group-hover:text-white text-[16px] font-normal">Javascript</p>
                            </div>
                            <div
                                class="skill-card bg-[#f9f9f9] flex flex-col items-center justify-center border border-white rounded-lg p-[20px] group hover:bg-[#0252CD] glass bg-none">
                                <div
                                    class="flex justify-center items-center shadow-[inset_0px_0px_5px_0px_rgba(0,49,200,0.1)] bg-white text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center mb-4 ease-in-out group-hover:bg-transparent">
                                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 576 512"
                                        height="35px" width="35px" xmlns="http://www.w3.org/2000/svg">
                                        <path
                                            d="M333.5,201.4c0-22.1-15.6-34.3-43-34.3h-50.4v71.2h42.5C315.4,238.2,333.5,225,333.5,201.4z M517,188.6 c-9.5-30.9-10.9-68.8-9.8-98.1c1.1-30.5-22.7-58.5-54.7-58.5H123.7c-32.1,0-55.8,28.1-54.7,58.5c1,29.3-0.3,67.2-9.8,98.1 c-9.6,31-25.7,50.6-52.2,53.1v28.5c26.4,2.5,42.6,22.1,52.2,53.1c9.5,30.9,10.9,68.8,9.8,98.1c-1.1,30.5,22.7,58.5,54.7,58.5h328.7 c32.1,0,55.8-28.1,54.7-58.5c-1-29.3,0.3-67.2,9.8-98.1c9.6-31,25.7-50.6,52.1-53.1v-28.5C542.7,239.2,526.5,219.6,517,188.6z M300.2,375.1h-97.9V136.8h97.4c43.3,0,71.7,23.4,71.7,59.4c0,25.3-19.1,47.9-43.5,51.8v1.3c33.2,3.6,55.5,26.6,55.5,58.3 C383.4,349.7,352.1,375.1,300.2,375.1z M290.2,266.4h-50.1v78.4h52.3c34.2,0,52.3-13.7,52.3-39.5 C344.7,279.6,326.1,266.4,290.2,266.4z">
                                        </path>
                                    </svg>
                                </div>
                                <p class="group-hover:text-white text-[16px] font-normal">Bootstrap</p>
                            </div>
                            <div
                                class="skill-card bg-[#f9f9f9] flex flex-col items-center justify-center border border-white rounded-lg p-[20px] group hover:bg-[#0252CD] glass bg-none">
                                <div
                                    class="flex justify-center items-center shadow-[inset_0px_0px_5px_0px_rgba(0,49,200,0.1)] bg-white text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center mb-4 ease-in-out group-hover:bg-transparent">
                                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" role="img"
                                        viewBox="0 0 24 24" height="35px" width="35px" xmlns="http://www.w3.org/2000/svg">
                                        <title></title>
                                        <path
                                            d="M12.001,4.8c-3.2,0-5.2,1.6-6,4.8c1.2-1.6,2.6-2.2,4.2-1.8c0.913,0.228,1.565,0.89,2.288,1.624 C13.666,10.618,15.027,12,18.001,12c3.2,0,5.2-1.6,6-4.8c-1.2,1.6-2.6,2.2-4.2,1.8c-0.913-0.228-1.565-0.89-2.288-1.624 C16.337,6.182,14.976,4.8,12.001,4.8z M6.001,12c-3.2,0-5.2,1.6-6,4.8c1.2-1.6,2.6-2.2,4.2-1.8c0.913,0.228,1.565,0.89,2.288,1.624 c1.177,1.194,2.538,2.576,5.512,2.576c3.2,0,5.2-1.6,6-4.8c-1.2,1.6-2.6,2.2-4.2,1.8c-0.913-0.228-1.565-0.89-2.288-1.624 C10.337,13.382,8.976,12,6.001,12z">
                                        </path>
                                    </svg>
                                </div>
                                <p class="group-hover:text-white text-[16px] font-normal">Tailwind</p>
                            </div>
                            <div
                                class="skill-card bg-[#f9f9f9] flex flex-col items-center justify-center border border-white rounded-lg p-[20px] group hover:bg-[#0252CD] glass bg-none">
                                <div
                                    class="flex justify-center items-center shadow-[inset_0px_0px_5px_0px_rgba(0,49,200,0.1)] bg-white text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center mb-4 ease-in-out group-hover:bg-transparent">
                                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 512 512"
                                        height="35px" width="35px" xmlns="http://www.w3.org/2000/svg">
                                        <path
                                            d="M256 8C119.3 8 8 119.2 8 256c0 136.7 111.3 248 248 248s248-111.3 248-248C504 119.2 392.7 8 256 8zM33 256c0-32.3 6.9-63 19.3-90.7l106.4 291.4C84.3 420.5 33 344.2 33 256zm223 223c-21.9 0-43-3.2-63-9.1l66.9-194.4 68.5 187.8c.5 1.1 1 2.1 1.6 3.1-23.1 8.1-48 12.6-74 12.6zm30.7-327.5c13.4-.7 25.5-2.1 25.5-2.1 12-1.4 10.6-19.1-1.4-18.4 0 0-36.1 2.8-59.4 2.8-21.9 0-58.7-2.8-58.7-2.8-12-.7-13.4 17.7-1.4 18.4 0 0 11.4 1.4 23.4 2.1l34.7 95.2L200.6 393l-81.2-241.5c13.4-.7 25.5-2.1 25.5-2.1 12-1.4 10.6-19.1-1.4-18.4 0 0-36.1 2.8-59.4 2.8-4.2 0-9.1-.1-14.4-.3C109.6 73 178.1 33 256 33c58 0 110.9 22.2 150.6 58.5-1-.1-1.9-.2-2.9-.2-21.9 0-37.4 19.1-37.4 39.6 0 18.4 10.6 33.9 21.9 52.3 8.5 14.8 18.4 33.9 18.4 61.5 0 19.1-7.3 41.2-17 72.1l-22.2 74.3-80.7-239.6zm81.4 297.2l68.1-196.9c12.7-31.8 17-57.2 17-79.9 0-8.2-.5-15.8-1.5-22.9 17.4 31.8 27.3 68.2 27.3 107 0 82.3-44.6 154.1-110.9 192.7z">
                                        </path>
                                    </svg>
                                </div>
                                <p class="group-hover:text-white text-[16px] font-normal">Wordpress</p>
                            </div>
                            <div
                                class="skill-card bg-[#f9f9f9] flex flex-col items-center justify-center border border-white rounded-lg p-[20px] group hover:bg-[#0252CD] glass bg-none">
                                <div
                                    class="flex justify-center items-center shadow-[inset_0px_0px_5px_0px_rgba(0,49,200,0.1)] bg-white text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center mb-4 ease-in-out group-hover:bg-transparent">
                                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 32 32"
                                        height="35px" width="35px" xmlns="http://www.w3.org/2000/svg">
                                        <path
                                            d="M 16 2 C 15.496094 2 15.003906 2.183594 14.625 2.5625 L 11.8125 5.40625 C 11.660156 5.488281 11.53125 5.605469 11.4375 5.75 L 2.5625 14.625 C 1.804688 15.378906 1.804688 16.617188 2.5625 17.375 L 14.625 29.4375 C 15.382813 30.191406 16.617188 30.191406 17.375 29.4375 L 29.4375 17.375 C 30.195313 16.621094 30.195313 15.382813 29.4375 14.625 L 17.375 2.5625 C 16.996094 2.183594 16.503906 2 16 2 Z M 16 4.03125 L 27.96875 16 L 16 27.96875 L 4.03125 16 L 12.3125 7.71875 L 14.0625 9.46875 C 14.015625 9.636719 14 9.816406 14 10 C 14 10.738281 14.402344 11.371094 15 11.71875 L 15 20.28125 C 14.402344 20.628906 14 21.261719 14 22 C 14 23.105469 14.894531 24 16 24 C 17.105469 24 18 23.105469 18 22 C 18 21.261719 17.597656 20.628906 17 20.28125 L 17 12.4375 L 20.0625 15.5 C 20.019531 15.660156 20 15.828125 20 16 C 20 17.105469 20.894531 18 22 18 C 23.105469 18 24 17.105469 24 16 C 24 14.894531 23.105469 14 22 14 C 21.828125 14 21.660156 14.019531 21.5 14.0625 L 17.9375 10.5 C 17.980469 10.339844 18 10.171875 18 10 C 18 8.894531 17.105469 8 16 8 C 15.816406 8 15.636719 8.015625 15.46875 8.0625 L 13.71875 6.3125 Z">
                                        </path>
                                    </svg>
                                </div>
                                <p class="group-hover:text-white text-[16px] font-normal">Git</p>
                            </div>
                            <div
                                class="skill-card bg-[#f9f9f9] flex flex-col items-center justify-center border border-white rounded-lg p-[20px] group hover:bg-[#0252CD] glass bg-none">
                                <div
                                    class="flex justify-center items-center shadow-[inset_0px_0px_5px_0px_rgba(0,49,200,0.1)] bg-white text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center mb-4 ease-in-out group-hover:bg-transparent">
                                    <svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 384 512"
                                        height="35px" width="35px" xmlns="http://www.w3.org/2000/svg">
                                        <path
                                            d="M14 95.7924C14 42.8877 56.8878 0 109.793 0H274.161C327.066 0 369.954 42.8877 369.954 95.7924C369.954 129.292 352.758 158.776 326.711 175.897C352.758 193.019 369.954 222.502 369.954 256.002C369.954 308.907 327.066 351.795 274.161 351.795H272.081C247.279 351.795 224.678 342.369 207.666 326.904V415.167C207.666 468.777 163.657 512 110.309 512C57.5361 512 14 469.243 14 416.207C14 382.709 31.1945 353.227 57.2392 336.105C31.1945 318.983 14 289.5 14 256.002C14 222.502 31.196 193.019 57.2425 175.897C31.196 158.776 14 129.292 14 95.7924ZM176.288 191.587H109.793C74.2172 191.587 45.3778 220.427 45.3778 256.002C45.3778 291.44 73.9948 320.194 109.381 320.416C109.518 320.415 109.655 320.415 109.793 320.415H176.288V191.587ZM207.666 256.002C207.666 291.577 236.505 320.417 272.081 320.417H274.161C309.737 320.417 338.576 291.577 338.576 256.002C338.576 220.427 309.737 191.587 274.161 191.587H272.081C236.505 191.587 207.666 220.427 207.666 256.002ZM109.793 351.795C109.655 351.795 109.518 351.794 109.381 351.794C73.9948 352.015 45.3778 380.769 45.3778 416.207C45.3778 451.652 74.6025 480.622 110.309 480.622C146.591 480.622 176.288 451.186 176.288 415.167V351.795H109.793ZM109.793 31.3778C74.2172 31.3778 45.3778 60.2173 45.3778 95.7924C45.3778 131.368 74.2172 160.207 109.793 160.207H176.288V31.3778H109.793ZM207.666 160.207H274.161C309.737 160.207 338.576 131.368 338.576 95.7924C338.576 60.2173 309.737 31.3778 274.161 31.3778H207.666V160.207Z">
                                        </path>
                                    </svg>
                                </div>
                                <p class="group-hover:text-white text-[16px] font-normal">Figma</p>
                            </div>
                        </div>
                        <button
                            class="btn bg-primary rounded-full justify-center text-white text-sm capitalize px-8 hover:bg-blue-500">See
                            More</button>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>