<template>

  <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmm  blog mmmmmmmmmmmmmmmmmmmmmm -->
   <section class=" bg-white  py-12 mt-16 rounded-2xl lg:px-10 px-5">
    <h5 class="font-bold text-2xl text-center underline decoration-[#adff00] decoration-2 ">MY BLOGS</h5>
<br>
<p class="text-lg text-neutral-400 text-center">
  Explore insightful posts on tech, development tips, and industry trends. Stay updated and inspired!
</p>
<div class="grid lg:grid-cols-2 grid-rows-1 pt-16 lg:gap-x-8 gap-y-8">
 
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmm  bg image mmmmmmmmmmmmmmmmmmmmmm -->
<div class="lg:block hidden">
<div  style="border-radius: 16px;background-image: url('/src/assets/images/sec.jpg');background-position: center;background-repeat: repeat;background-size: cover;widows: 100%;height: 100%;">
<div class="h-full w-full rounded-2xl bg-black bg-opacity-40">
<div class="pt-[27rem] px-5">
  <p class="text-center text-white italic text-2xl ">Frameworks I use more often.</p>
<h4 class="text-white text-3xl font-bold">Vue and Flutter algorythm is easily to learn!!</h4>
</div>
</div>
</div>

</div>
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmm 
   project
    mmmmmmmmmmmmmmmmmmmmmm -->
<div class="">
  <div class="grid lg:grid-cols-2 lg:gap-x-6 gap-y-8 ">
<a href="https://quickfixer.vercel.app/" target="_blank" rel="noopener noreferrer">
  <div class="border border-gray-400 rounded-lg py-12 h-full text-center hover:bg-slate-200 cursor-pointer">
  <p class="text-gray-500">Website</p>
  <br>
  <h4 class="font-bold text-xl ">Built a website using <br> Vue </h4>
  <br>
  
  <br>
  <p class="text-gray-500">November,2023</p>
</div>
</a>
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmm 
   second blog
    mmmmmmmmmmmmmmmmmmmmmm -->
    <a href="https://quickfixer.vercel.app/" target="_blank" rel="noopener noreferrer">
  <div class="border border-gray-400 rounded-lg py-12 h-full text-center hover:bg-slate-200 cursor-pointer">
  <p class="text-gray-500">Website</p>
  <br>
  <h4 class="font-bold text-xl ">Built a website using TailwindCss </h4>
  
  <br>
  <br>
  <p class="text-gray-500">September,2022</p>
</div>
</a>

<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmm 
   third blog
    mmmmmmmmmmmmmmmmmmmmmm -->
    <a href="https://quickfixer.vercel.app/" target="_blank" rel="noopener noreferrer">
  <div class="border border-gray-400 rounded-lg py-12 h-full text-center hover:bg-slate-200 cursor-pointer">
  <p class="text-gray-500">Website</p>
  <br>
  <h4 class="font-bold text-xl ">Built a website using Bootstrap </h4>
  
  <br>
  <br>
  <p class="text-gray-500">May,2022</p>
</div>
</a>

<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmm 
   fourth blog
    mmmmmmmmmmmmmmmmmmmmmm -->
    <a href="https://quickfixer.vercel.app/" target="_blank" rel="noopener noreferrer">
  <div class="border border-gray-400 rounded-lg py-12 h-full text-center hover:bg-slate-200 cursor-pointer">
  <p class="text-gray-500">Website</p>
  <br>
  <h4 class="font-bold text-xl ">Built a website using TailwindCss </h4>
  
  <br>
  <br>
  <p class="text-gray-500">March,2023</p>
</div>
</a>

</div>
</div>
</div>
   </section>

  <section class=" bg-[#1e1f24]  py-12 mt-16 rounded-2xl lg:px-10 px-5">
    <h5 class="font-bold text-2xl text-center underline decoration-[#adff00] decoration-2 text-white">TESTIMONIALS</h5>
<br><p class="text-lg text-neutral-400 text-center">
  Read what my clients have to say about working with me.
</p>

<div class="grid lg:grid-cols-3 grid-rows-1 pt-16 lg:gap-x-6 gap-y-8">

  <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmm first person mmmmmmmmmmmmmmmmmm -->
   <div class="bg-white px-5 py-12 rounded-2xl shadow-slate-500 shadow-lg ">
    <img :src="Fpic" alt="Client" class="w-24 h-24 rounded-full mx-auto object-cover border-[4px] border-[#adff00]">
    <h5 class="text-center font-bold text-2xl pt-3">Fuseni Hamza</h5>
    <h5 class="text-center text-gray-400  text-xl ">MERN Stack Developer</h5>
    <br>
    
<p class="text-ellipsis text-gray-600 px-2 text-base" >
  Working with Bonnah John has been a great experience! They truly understand the tech and delivered exactly what I needed.
</p>
   </div>
   <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmm second person mmmmmmmmmmmmmmmmmm -->
   <div class="bg-white px-5 py-12 rounded-2xl shadow-slate-500 shadow-lg">
    <img :src="Spic" alt="Client" class="w-24 h-24 rounded-full mx-auto object-cover border-[4px] border-[#adff00]">
    <h5 class="text-center font-bold text-2xl pt-3">Yahaya Mohammed</h5>
    <h5 class="text-center text-gray-400  text-xl ">Web Developer</h5>
    <br>
    
<p class="text-ellipsis text-gray-600 px-2 text-base">
  Efficient, knowledgeable, and attentive to detail. John Bonnah brought our vision to life seamlessly. Exceptional work!
</p>
   </div>
   <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmm third person mmmmmmmmmmmmmmmmmm -->
   <div class="bg-white px-5 py-12 rounded-2xl shadow-slate-500 shadow-lg">
    <img :src="Tpic" alt="Client" class="w-24 h-24 rounded-full mx-auto object-cover border-[4px] border-[#adff00]">
    <h5 class="text-center font-bold text-2xl pt-3">Kofi Amoako</h5>
    <h5 class="text-center text-gray-400  text-xl ">.Net Web Developer</h5>
    <br>
    
<p class="text-ellipsis text-gray-600 px-2 text-base">
  Bonnah John consistently brought fresh ideas to our project and delivered with high quality and dedication. Highly recommended!
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
  