<template>
    <div class="contact-form">
        <div class="bg-[#F8F6F5]">
            <div
                class="grid gap-[25px] bg-white rounded-3xl items-center lg:gap-0 grid-cols-1 sm:grid-cols-1 md:grid-cols-1 lg:grid-cols-2 xl:grid-cols-3">
                <div
                    class="bg-primary text-white rounded-3xl lg:rounded-l-3xl lg:rounded-r-[0] space-y-[30px] py-[30px] md:py-[60px] lg:py-[90px] px-[20px] md:px-[50px]">
                    <div class="border border-[#fff] rounded-[20px] px-[30px] py-[35px]">
                        <h3 class="text-[18px] md:text-[22px] font-semibold mb-[20px] leading-none">Office Address</h3>
                        <div class="flex items-center space-x-[15px]">
                            <div
                                class="flex justify-center items-center shrink-0 bg-white text-primary-color w-[48px] h-[48px] leading-[50px] text-[25px] text-center rounded-full">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                    stroke="currentColor" class="w-6 h-6 text-black">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                                </svg>
                            </div>
                            <p>2750 Quadra Street Victoria Road, New York, USA</p>
                        </div>
                    </div>
                    <div class="border border-[#fff] rounded-[20px] px-[30px] py-[35px]">
                        <h3 class="text-[18px] md:text-[22px] font-semibold mb-[20px] leading-none">Phone Number</h3>
                        <div class="flex items-center space-x-[15px]">
                            <div
                                class="flex justify-center items-center shrink-0 bg-white text-primary-color w-[48px] h-[48px] leading-[50px] text-[25px] text-center rounded-full">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                    stroke="currentColor" class="w-6 h-6 text-black">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                                </svg>
                            </div>
                            <div>
                                <a href="tel:1234567898" class="block hover:text-primary-color">(+123) 456-7898</a>
                                <a href="tel:1234567899" class="block hover:text-primary-color">(+123) 456-7899</a>
                            </div>
                        </div>
                    </div>
                    <div class="border border-[#fff] rounded-[20px] px-[30px] py-[35px]">
                        <h3 class="text-[18px] md:text-[22px] font-semibold mb-[20px] leading-none">Email Us</h3>
                        <div class="flex items-center space-x-[15px]">
                            <div
                                class="flex justify-center items-center shrink-0 bg-white text-primary-color w-[48px] h-[48px] leading-[50px] text-[25px] text-center rounded-full">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                    stroke="currentColor" class="w-6 h-6 text-black">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                                </svg>
                            </div>
                            <div>
                                <a href="mailto:support@plama.com"
                                    class="block hover:text-primary-color">support@plama.com</a>
                                <a href="mailto:info@plama.com" class="block hover:text-primary-color">info@plama.com</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="xl:col-span-2 px-[20px] md:px-[50px] lg:px-[50px] xl:px-[90px] py-[30px] md:py-[50px]">
                    <form class="space-y-[25px]">
                        <div
                            class="grid gap-[25px] grid-cols-1 sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-2 xl:grid-cols-2">
                            <input id="name" placeholder="Your Name"
                                class="bg-white rounded-[6px] text-[#384179] border border-[#ededed] h-[56px] block w-full py-[5px] px-[25px] placeholder-[#384179] focus:outline-none"
                                type="text" name="name">

                            <input id="email" placeholder="Your Email"
                                class="bg-white rounded-[6px] text-[#384179] border border-[#ededed] h-[56px] block w-full py-[5px] px-[25px] placeholder-[#384179] focus:outline-none"
                                type="text" name="email">
                        </div>

                        <input id="subject" placeholder="Your Subject"
                            class="bg-white rounded-[6px] text-[#384179] border border-[#ededed] h-[56px] block w-full py-[5px] px-[25px] placeholder-[#384179] border-[#82839E]focus:outline-none"
                            type="text" name="subject">

                        <input id="number" placeholder="Your Number"
                            class="bg-white rounded-[6px] text-[#384179] border border-[#ededed] h-[56px] block w-full py-[5px] px-[25px] placeholder-[#384179] focus:outline-none"
                        type="text" name="number">

                    <textarea id="comment" placeholder="Enter Message..." name="comment" rows="8"
                        class="bg-white rounded-[6px] text-[#384179] border border-[#ededed] block w-full py-[10px] px-[25px] placeholder-[#384179] focus:outline-none"></textarea>

                    <div class="text-center">
                        <button type="submit"
                            class="py-[15px] px-[30px] inline-block rounded-[6px] bg-primary text-white font-semibold text-[16px] md:text-[18px] transition duration-500 ease-in-out hover:bg-black-color">Send
                            Your Message</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</div></template>

<script setup>

</script>

<style lang="scss" scoped></style>