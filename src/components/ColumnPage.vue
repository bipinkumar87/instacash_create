<template>
<div class="columns-4 container mx-auto">
    <div class="one w-80 h-8 bg-slate-500">
        
    </div>
    <div class="two w-80 h-8 bg-green-950 mt-5">

    </div>
    <div class="two w-80 h-8 bg-green-900 mt-5"></div>
    <div class="two w-80 h-8 bg-green-800 mt-5"></div>
    <div class="two w-80 h-8 bg-green-900 mt-5"></div>
    <div class="two w-80 h-8 bg-green-800 mt-5"></div>
    <div class="two w-80 h-8 bg-green-700 mt-5"></div>
    <div class="two w-80 h-8 bg-green-950 mt-5"></div>
    <div class="two w-80 h-8 bg-green-950 mt-5"></div>
    <div class="two w-80 h-8 bg-green-950 mt-5"></div>
    <div class="two w-80 h-8 bg-green-950 mt-5"></div>
    <div class="two w-80 h-8 bg-green-950 mt-5"></div>
    <div class="two w-80 h-8 bg-green-950 mt-5"></div>
</div>
<div>
    <p class=" border-zinc-400 border-4 my-10">When controlling the flow of text, using the CSS property
    <span class="inline  border-zinc-400 border-4 my-2">display: inline</span>
    will cause the text inside the element to wrap normally.</p>
  <p class=" border-zinc-400 border-4 my-4">
    While using the property <span class="inline-block border-zinc-400 border-4 my-2">display: inline-block</span>
    will wrap the element to prevent the text inside from extending beyond its parent.</p>
    
    <p class=" border-zinc-400 border-4 my-4">
    Lastly, using the property <span class="block  border-zinc-400 border-4 my-4">display: block</span>
    will put the element on its own line and fill its parent.
    </p>
  </div>
  <div class="zindex flex ">
    <div class="one w-40 h-40 bg-amber-600 rounded-full z-40 relative border-4 border-blue-800 "></div>
    <div class="one w-40 h-40 bg-slate-600 rounded-full z-40 relative right-5 border   border-white"></div>
    <p class="w-24 h-24 rounded-full border border-white bg-indigo-600 flex items-center justify-center text-white text-base font-medium relative shadow-md shadow-black/45 z-50"> z-50</p>
      <p class="w-24 h-24 rounded-full border border-white bg-indigo-600 flex items-center justify-center text-white text-base font-medium relative shadow-md shadow-black/45 -translate-x-8 z-40"> z-40</p>
      <p class="w-24 h-24 rounded-full border border-white bg-indigo-600 flex items-center justify-center text-white text-base font-medium relative shadow-md shadow-black/45 -translate-x-16 z-30"> z-30</p>
      <p class="w-24 h-24 rounded-full border border-white bg-indigo-600 flex items-center justify-center text-white text-base font-medium relative shadow-md shadow-black/45 -translate-x-24 z-20"> z-20</p>
      <p class="w-24 h-24 rounded-full border border-white bg-indigo-600 flex items-center justify-center text-white text-base font-medium relative shadow-md shadow-black/45 -translate-x-32 z-10"> z-10</p>
      <p class="w-24 h-24 rounded-full border border-white bg-indigo-600 flex items-center justify-center text-white text-base font-medium relative shadow-md shadow-black/45 -translate-x-40 z-0"> z-0</p>
  </div>
<div class="flex flex-row space-x-4">
    <div class="basis-1/4 bg-green-600 ">hello</div>
    <div class="basis-1/4 bg-green-600 hover:basis-1/2 space-x-4" > hello</div>
    <div class="basis-1/2 bg-green-600">hello</div>
</div>
</template>

<script setup>

</script>

<style scoped>

</style>