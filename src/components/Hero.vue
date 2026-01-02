<template>
    <div class="min-h-screen overflow-hidden">

        <!-- Main Content Container -->
        <div class="flex items-center justify-center px-4 sm:px-6 lg:px-8">
            <div class="max-w-6xl w-full">
                <!-- Header -->
                <header class="mb-9 sm:mb-11 pt-10">
                    <nav class="flex shadow items-center rounded-full px-6 py-4 bg-white justify-between">
                        <div>
                            <img class="" src="../assets/logo.png" alt="">
                        </div>

                        <div class="hidden md:flex items-center  gap-8">
                            <a href="#"
                                class="text-gray-400 transition-all duration-400 hover:text-gray-900 text-sm">How it
                                Works</a>
                            <a href="#"
                                class="text-gray-400 transition-all duration-400 hover:text-gray-900 text-sm">Pricing</a>
                            <a href="#"
                                class="text-gray-400 transition-all duration-400 hover:text-gray-900 text-sm">Use
                                Case</a>
                            <a href="#"
                                class="text-gray-400 transition-all duration-400 hover:text-gray-900 text-sm">FAQ</a>
                        </div>

                        <button
                            class="bg-blue-500 hover:bg-blue-600  text-white px-5 py-2 rounded-full text-sm font-normal">
                            Contact Sales
                        </button>
                    </nav>
                </header>

                <!-- Hero Section -->
                <div class="text-center items-center flex flex-col">
                    <!-- Badge -->
                    <div class="mb-5">
                        <img src="./assets/automation.png" alt="">
                    </div>

                    <!-- Heading -->
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold mb-6 leading-tight">
                        <span class="text-blue-500">iMessage</span>
                        <span class="text-gray-900"> Automation</span>
                        <br />
                        <span class="text-gray-900">for Teams and AI</span>
                        <br />
                        <span class="text-gray-900">Workflows.</span>
                    </h1>

                    <!-- Description -->
                    <p class="text-sm text-gray-700 mb-8 ">
                        Coup lets you, your team, or AI workflows send iMessages directly from <br> your phone number,
                        running securely on your Mac or Mac Mini.
                    </p>

                    <!-- CTAs -->
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button
                            class="w-full sm:w-auto transition-all duration-300 cursor-pointer bg-blue-500 hover:bg-blue-600 text-white px-5 py-2 rounded-full">
                            Get Started
                        </button>
                        <button
                            class="w-full sm:w-auto border border-gray-300 hover:border-gray-400 text-gray-900 px-5 py-2 rounded-full font-medium flex items-center justify-center gap-2">
                            <svg width="18" height="22" viewBox="0 0 19 22" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M15.4077 11.6258C15.3979 9.82322 16.2107 8.4627 17.8557 7.46073C16.9353 6.13951 15.5448 5.41259 13.7088 5.27015C11.9707 5.13263 10.0711 6.28686 9.37585 6.28686C8.64145 6.28686 6.95723 5.31927 5.6353 5.31927C2.90333 5.36348 0 7.50494 0 11.8615C0 13.1484 0.235008 14.4778 0.705025 15.8498C1.33171 17.6523 3.59367 22.0728 5.95355 21.9991C7.18734 21.9696 8.05883 21.1199 9.66472 21.1199C11.2216 21.1199 12.0295 21.9991 13.4053 21.9991C15.7847 21.9647 17.8313 17.947 18.4286 16.1395C15.2364 14.6317 15.4077 11.7191 15.4077 11.6258ZM12.6366 3.56092C13.9732 1.96955 13.8508 0.52063 13.8116 0C12.6317 0.0687625 11.2657 0.805504 10.4872 1.71415C9.63045 2.68665 9.12616 3.88999 9.23387 5.2456C10.5117 5.34383 11.677 4.68567 12.6366 3.56092Z"
                                    fill="#1D2026" />
                            </svg>

                            <svg width="1" height="18" viewBox="0 0 1 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <line x1="0.25" y1="-1.09278e-08" x2="0.250001" y2="18" stroke="#6C788F"
                                    stroke-width="0.5" />
                            </svg>
                            Download the Mac app
                        </button>
                    </div>

                    <!-- Scroll Indicator -->
                    <div class="mt-16 sm:mt-20 text-center">
                        <p class="text-gray-600 text-sm mb-2">Scroll to learn more</p>
                        <svg class="w-6 h-6 mx-auto text-gray-400 animate-bounce" fill="none" stroke="currentColor"
                            viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>