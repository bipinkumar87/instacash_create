<template>
 <div class="grid grid-cols-4 gap-4 hover:grid-cols-3">
<div class="border-b-orange-800 bg-pink-950" >1</div>
<div class="border-b-orange-800 bg-pink-950">2</div>
<div class="border-b-orange-800 bg-pink-950">3</div>
<div class="border-b-orange-800 bg-pink-950">4</div>
<div class="border-b-orange-800 bg-pink-950">5</div>
<div class="border-b-orange-800 bg-pink-950">6</div>
<div class="border-b-orange-800 bg-pink-950">7</div>
<div class="border-b-orange-800 bg-pink-950">8</div>
<div class="border-b-orange-800 bg-pink-950">9</div>
</div>
<div class="grid grid-cols-4 gap-4 bg-slate-500">
    <div class="bg-green-700">011</div>
    <div class="bg-green-700">02</div>
    <div class="bg-green-700">03</div>
    <div class="bg-green-700">04</div>
    <div class="bg-green-700">05</div>
    <div class="grid grid-cols-subgrid gap-4 col-span-3 bg-red-700">
      <div class="col-start-2 bg-blue-500">06</div>
    </div>
  </div>
  <div class="grid grid-cols-4 gap-4 bg-slate-500 my-5">
    <div class="bg-green-500">01</div>
    <div class="bg-green-500">02</div>
    <div class="bg-green-500">03</div>
    <div class="bg-green-500">04</div>
    <div class="bg-green-500">05</div>
    <div class="grid grid-cols-subgrid gap-4 col-span-3 bg-red-900">
      <div class="col-span-2 col-start-2 bg-blue-700">06</div>
    </div>
  </div>
  <div class="grid bg-yellow-600 xl:grid-cols-4 gap-4 md:grid-cols-2 md:bg-yellow-800 sm:grid-cols-1 sm:bg-yellow-400">
    <div class="bg-blue-600 md:bg-blue-500 sm:bg-blue-400">1</div>
    <div class="bg-blue-600 md:bg-blue-500 sm:bg-blue-400">2</div>
    <div class="bg-blue-600 md:bg-blue-500 sm:bg-blue-400">3</div>
    <div class="bg-blue-600 md:bg-blue-500 sm:bg-blue-400">4</div>
    <div class="bg-blue-600 md:bg-blue-500 sm:bg-blue-400">5</div>
    <div class="bg-blue-600 md:bg-blue-500 sm:bg-blue-400">6</div>
    <div class="bg-blue-600 md:bg-blue-500 sm:bg-blue-400">7</div>
    <div class="bg-blue-600 md:bg-blue-500 sm:bg-blue-400">8</div>
  </div>
</template>

<script setup>

</script>

<style scoped>

</style>