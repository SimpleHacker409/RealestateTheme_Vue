<template>

<div class="w-full min-h-screen">
    <section class="relative py-1 px-0">
        <nav class=" z-20 relative flex items-center justify-between px-2 py-6 w-4/5 mx-auto">
        <a href="#" class=" text-4xl sm:text-3xl font-semibold tracking-wide text-codeacademy">{{ title }}</a>
        <ul class="items-center space-x-8 hidden lg:flex ">
            <div v-for="menu in menuitems" v-bind:key="menu">
                <li class="text-lg font-medium tracking-wider group text">
                <div class="">    
                <a class="hover:underline" href="#">{{ menu }}</a>
                </div>
                </li>
            </div>
        </ul>
        <button type="button" class="items-center px-4 py-2 h-16 border border-transparent shadow-sm text-lg text-white bg-codeacademy hover:bg-codeacademy hover:shadow-xl transition-shadow duration-300 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
          <CheckIcon class="-ml-1 mr-2 h-5 w-5" aria-hidden="true" />
          Get Started
        </button>
        </nav>
        <div class=" z-20 relative justify-between py-24 w-4/5 mx-auto">
            
            <div class="text-white sm:text-black">
                <span class="font-bold text-6xl pt-4 tracking-wide leading-relaxed">Easy to Find Your Next Best</span>
                <h1 class="font-bold text-6xl tracking-wide leading-relaxed">Pergect Place</h1>
                <p class="max-w-md pt-5 tracking-wide leading-relaxed ">An Agency, in broad terms, is any relationship between two parties in which one the agent reprecent the other the priocinple in day-to-day transactions.</p>
                <div class="flex pt-5 space-x-6">
                    <button class="flex justify-center items-center h-12 px-6 w-auto focus:outline-none hover:bg-codeacademy bg-codeacademy text-white hover:shadow-xl transition-shadow duration-300">Learn More</button>
                    <button class="hover:animate-none animate-pulse bg-blue-300 hover:bg-blue-400 text-gray-800 font-bold py-2 px-4 rounded-full items-center border-4 border-blue-200">
                    <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><path d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z"/></svg>
                    </button>
                </div>
                
                <div class="mt-10 flex justify-center text-gray-600 bg-blue-100 w-1/2 sm:w-1/6 py-2 rounded-md text-sm">
                    <button class="px-3 hover:text-codeacademy">Rent</button>
                    <button class="px-3 hover:text-codeacademy">Buy</button>
                    <button class="px-3 hover:text-codeacademy">Sell</button>
                </div>

                <div class="flex justify-between py-5 px-6 rounded-md shadow-xl bg-white w-full xl:w-10/12">
                    <div class="w-1/4 h-3  search-option">
                        <p class="text-lg font-medium text-gray-500 py-2">Location</p>
                        <select class="selectedCam focus:outline-none" @change="dosomething" >
                            <option value="" disabled selected>Milan, Italy</option>
                            <option value="1">Vennice, Italy</option>
                            <option value="2">Rome, Italy</option>
                        </select >
                    </div>
                    <div class="w-full md:w-1/4 h-3 search-option">
                         <p class="text-lg font-medium text-gray-500 py-2">Home Type</p>
                        <select class="selectedCam focus:outline-none" @change="dosomething" >
                            <option value="" disabled selected>Duplex House</option>
                            <option value="1">Single Room</option>
                            <option value="2">Full Appartment</option>
                        </select >
                    </div>
                    <div class="w-1/4 h-3">
                         <p class="text-lg font-medium text-gray-500 py-2">Range</p>
                        <select class="selectedCam focus:outline-none" @change="dosomething" >
                            <option value="" disabled selected>$10,000-$60,000</option>
                            <option value="1">$2,000-$10,000</option>
                            <option value="2">$60,000-$100,000</option>
                        </select >
                    </div>
                    <button class="flex justify-center items-center h-16 px-6 w-auto focus:outline-none hover:bg-codeacademy bg-codeacademy text-white hover:shadow-xl transition-shadow duration-300">Search Property</button>
                </div>
            </div>
        </div>
        <div class="absolute flex justify-end inset-0 h-screen z-10 ">
            <img src="../assets/download.jpg" alt="" class="h-screen sm:w-1/2 w-full">
        </div>

    </section>
    
    <!--Branding Section-->
    <div>
        <img src="">
    </div>
</div>
</template>

<script>

export default {
  name: 'LandingPage',
  data() {
      return {
          title: "Building.RS",
          menuitems: ["Home", "About Us", "Properties", "Agent", "Contact"]
      }
  }
}
</script>


<style scoped>
.banner-text{
    overflow: hidden;
}
.search-option{
    border-right: solid 2px rgba(169, 169, 169, 0.507);
    height:60px;
}
</style>
