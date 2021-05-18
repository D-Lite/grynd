<template>
 <nav class="flex flex-wrap items-center justify-between p-5">
   <div class="logo">
     <a href="./home" class="text-4xl font-bold text-left text-white"><p>GRYND.</p></a>
   </div>
  <div class="flex md:hidden">
    <button id="hamburger" class="bg-gray-700">
      <img class="toggle block" src="https://img.icons8.com/fluent-systems-regular/2x/menu-squared-2.png" width="40" height="40" />
      <img class="toggle hidden" src="https://img.icons8.com/fluent-systems-regular/2x/close-window.png" width="40" height="40" />
    </button>
  </div>
   <div class="toggle hidden md:flex w-full md:w-auto text-right text-semibold mt-5 md:mt-0 border-t-2 border-blue-900 md:border-none">
     <a href="./" class="text-sm text-white block md:inline-block hover:text-blue-500 px-3 py-3 border-b-2 md:border-none"><p>Home</p></a>
     <a href="./" class="text-sm text-white block md:inline-block hover:text-blue-500 px-3 py-3 border-b-2 md:border-none"><p>About</p></a>
     <a href="./" class="text-sm text-white block md:inline-block hover:text-blue-500 px-3 py-3 border-b-2 md:border-none"><p>Fitness</p></a>
     <a href="./" class="text-sm text-white block md:inline-block hover:text-blue-500 px-3 py-3 border-b-2 md:border-none"><p>Spa</p></a>
     <a href="./" class="text-sm text-white block md:inline-block hover:text-blue-500 px-3 py-3 border-b-2 md:border-none"><p>Blog</p></a>

   </div>
 </nav>
</template>

<script>

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  mounted() {
    document.getElementById("hamburger").onclick = function toggleMenu() {
    const navToggle = document.getElementsByClassName("toggle");
    for (let i = 0; i < navToggle.length; i++) {
    navToggle.item(i).classList.toggle("hidden");
  }
};

  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 
</style>
