<template>
  <div class="flex justify-center pb-16 tracking-wide leading-loose">
        <div class="container relative overflow-hidden px-4 sm:px-8 mx-auto">
                    <div class="absolute opacity-25 card-image pt-20">
                        <svg 
                            class="w-full h-full text-white overflow-hidden fill-current"
                            xmlns="http://www.w3.org/2000/svg" 
                            width="512" height="512.002" 
                            viewBox="0 0 512 512.002">
                            <g transform="translate(0 0.002)">
                                <path d="M224 32.01c-123.5 0-224 100.5-224 224s100.5 224 224 224s224-100.5 224-224S347.5 32.01 224 32.01zM224 416c-88.22 0-160-71.78-160-160s71.78-159.1 160-159.1s160 71.78 160 159.1S312.2 416 224 416z"/>
                            </g>
                        </svg>
                    </div>

            <div class="flex justify-center rounded-xl shadow-lg bg-subscribe-card">

                <div class="card text-center  px-8 py-10 w-8/12">

                    <div class="card-text">
                        <h1 class="text-xl md:text-2xl font-bold leading-tight text-white">Get the latest components right into your inbox!</h1>
                        <p class="text-base md:text-lg text-white mt-3 ">Join 4k+ happy subscribers!</p>
                    </div>

                    <div class="card-mail flex items-center my-10 bg-white p-3 rounded-xl">
                        <input type="email" class="rounded-l-md w-full text-base md:text-lg px-3 py-2" placeholder="Enter Your Email">
                        <button class="bg-codeacademy hover:bg-blue-700 text-white font-bold capitalize px-3 py-2 text-base md:text-lg md:w-48 rounded-xl border-t border-r border-b focus:outline-none">subscribe</button>
                    </div>
                </div>
            </div>
        </div>
  </div>
</template>

<script>
export default {
  name: 'SubscribeCard',
  props: {
  }
}
</script>

<style scoped>

</style>
