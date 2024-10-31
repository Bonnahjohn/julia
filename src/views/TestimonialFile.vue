<template>
  <section class=" bg-[#1e1f24]  py-12 mt-16 rounded-2xl lg:px-10 px-5">
    <h5 class="font-bold text-2xl text-center underline decoration-[#adff00] decoration-2 text-white">TESTIMONIALS</h5>
<br><p class="text-lg text-neutral-400 text-center">
Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur omnis autem tenetur.
</p>

<div class="grid lg:grid-cols-3 grid-rows-1 pt-16 lg:gap-x-6 gap-y-8">

  <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmm first person mmmmmmmmmmmmmmmmmm -->
   <div class="bg-white px-5 py-12 rounded-2xl shadow-slate-500 shadow-lg">
    <img :src="Fpic" alt="Client" class="w-24 h-24 rounded-full mx-auto object-cover border-[4px] border-[#adff00]">
    <h5 class="text-center font-bold text-2xl pt-3">Fuseni Hamza</h5>
    <h5 class="text-center text-gray-400  text-xl ">Merns Stack</h5>
    <br>
    
<p class="text-ellipsis text-gray-600 px-2 text-base" >
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum illo rerum inventore! Repellendus, perferendis? Nostrum doloribus assumenda suscipit alias doloremque!
</p>
   </div>
   <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmm second person mmmmmmmmmmmmmmmmmm -->
   <div class="bg-white px-5 py-12 rounded-2xl shadow-slate-500 shadow-lg">
    <img :src="Spic" alt="Client" class="w-24 h-24 rounded-full mx-auto object-cover border-[4px] border-[#adff00]">
    <h5 class="text-center font-bold text-2xl pt-3">Yahaya Mohammed</h5>
    <h5 class="text-center text-gray-400  text-xl ">Web Developer</h5>
    <br>
    
<p class="text-ellipsis text-gray-600 px-2 text-base">
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum illo rerum inventore! Repellendus, perferendis? Nostrum doloribus assumenda suscipit alias doloremque!
</p>
   </div>
   <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmm third person mmmmmmmmmmmmmmmmmm -->
   <div class="bg-white px-5 py-12 rounded-2xl shadow-slate-500 shadow-lg">
    <img :src="Tpic" alt="Client" class="w-24 h-24 rounded-full mx-auto object-cover border-[4px] border-[#adff00]">
    <h5 class="text-center font-bold text-2xl pt-3">Kofi Amoako</h5>
    <h5 class="text-center text-gray-400  text-xl ">.Net Web Developer</h5>
    <br>
    
<p class="text-ellipsis text-gray-600 px-2 text-base">
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum illo rerum inventore! Repellendus, perferendis? Nostrum doloribus assumenda suscipit alias doloremque!
</p>
   </div>
</div>
  </section>

  </template>
 
 <script>
 import Fpic from '@/assets/images/banner.jpg'
 import Spic from '@/assets/images/what.jpg'
 import Tpic from '@/assets/images/third.jpg'
export default{
  data(){
return{
Fpic,
Spic,
Tpic
}
  }
}
</script>
  