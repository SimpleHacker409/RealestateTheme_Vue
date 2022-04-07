<template>
  <div class="hello flex justify-center flex-col items-center">
    <h1 class="text-5xl">WellCome!</h1>
    <div class="flex flex-col items-center bg-gray-100 w-1/2 p-10 rounded-xl shadow-xl">
      <img class="h-64 w-64 rounded-full object-cover" src="https://source.unsplash.com/random" alt="">
      <h4 class="text-2xl font-thin">Image Text</h4>
      <p class="text-center mt-3">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Praesentium amet, necessitatibus excepturi nemo dolore adipisci tenetur fuga aut exercitationem voluptate!</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
