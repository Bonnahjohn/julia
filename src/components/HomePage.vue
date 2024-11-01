<template >
    <nav class="w-full fixed z-30  py-4 " :class=" [isScroll?'backdrop-blur-lg border-2 shadow-md bg-gray-800/50':'bg-transparent']">
     <div class="container mx-auto px-3 lg:px-6 flex justify-between items-center">

      <div>
        <strong class=" text-3xl font-bold" :class="[isScroll?'text-[#adff00]':'text-white']">Tenace</strong>
      </div>

      <button class="bg-[#adff00] hover:bg-opacity-50 hover:text-white px-10 py-3 font-bold text-lg rounded-lg">DWONLOAD  CV</button>

     </div>
    </nav>


    <main class="container px-3 lg:px-6 mx-auto pt-24">

<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmm hero section mmmmmmmmmmmmmmmm -->
 <section class=" bg-[#1e1f24] rounded-2xl py-14">
<div class="flex flex-col justify-center text-center text-white">
   <img :src="image" alt="hero image" class="w-40 h-40 rounded-full mx-auto object-cover">
   <br>
   <br>
          <p class=" font-bold  text-2xl "> Hello There, I'm </p>
          <h1 class="lg:text-[90px] text-[45px] font-bold  ">John <span class="text-[#adff00]">Bonnah</span></h1>
         <p class="text-2xl ">Ghana based <strong>Dumerica_</strong></p>
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmm 
 flex buttons
mmmmmmmmmmmmmmmm -->
         <div class="flex mx-auto pt-12 space-x-6">
          <a class="bg-[#adff00] hover:bg-transparent hover:border-[#adff00] border-[#adff00] border-2 hover:text-white
           lg:px-10 px-5 py-3 font-bold text-lg rounded-md text-black" href="#hire">HIRE ME</a>

           <a class="bg-[#adff00] hover:bg-transparent hover:border-[#adff00] border-[#adff00] border-2 hover:text-white
           lg:px-10 px-5 py-3 font-bold text-lg rounded-md text-black" href="#about">ABOUT ME</a>
         </div>
</div>
 </section>
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmm welcome to my world mmmmmmmmmmmmmmmm -->
 <section class=" bg-white  py-12 mt-16 rounded-2xl px-10">
  <h2 class="font-extrabold text-2xl text-center underline " style="text-decoration-color: #adff00;text-decoration-thickness: 3px;">WELCOME TO MY WORLD</h2>
<br>
 <p class="text-gray-400 text-center text-xl  lg:visible hidden">I'm a young tech enthasist and plumber who love to take <br> risk.I grew up in a non-tech family in Ghana</p>
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmm for mobile only mmmmmmmmmmmmmmmm -->
 <p class="text-gray-400 text-center text-xl ">I'm a young tech enthasist and plumber who love to take  risk.I grew up in a non-tech family in Ghana</p>
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmm the three cards mmmmmmmmmmmmmmmm -->
  <div class="grid lg:grid-cols-3 grid-row-1 gap-8 mt-14">
<div class="border-gray-400 border rounded-2xl px-10 py-12">
  <h3 class="text-3xl font-bold">Creativity</h3>
  <br>
  <p class="text-neutral-400 text-lg ">
    Bringing innovative ideas to life,
    crafting solutions that stand out and inspire.</p>
</div>
<div class="border-gray-400 border rounded-2xl px-10 py-12">
  <h3 class="text-3xl font-bold">Dedication</h3>
  <br>
  <p class="text-neutral-400 text-lg break-words">
    Committed to delivering excellence in every project,
    ensuring quality and attention to detail.
  </p>
</div>
<div class="border-gray-400 border rounded-2xl px-10 py-12">
  <h3 class="text-3xl font-bold">Hard Work</h3>
  <br>
  <p class="text-neutral-400 text-lg">
 Driven by a strong work ethic,
 always striving to achieve the best possible outcomes.
  </p>
  </div>
  </div>
</section>
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   sucess story
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <section class=" bg-[#1e1f24]  py-16 mt-16 rounded-2xl lg:px-10 px-5">
<div class="grid lg:grid-cols-4 grid-cols-2 lg:gap-x-16 gap-y-10">
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   groups
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
<div>
  <svg xmlns="http://www.w3.org/2000/svg"   fill="black" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-12 mx-auto text-[#adff00]">
  <path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 0 0 3.741-.479 3 3 0 0 0-4.682-2.72m.94 3.198.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0 1 12 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 0 1 6 18.719m12 0a5.971 5.971 0 0 0-.941-3.197m0 0A5.995 5.995 0 0 0 12 12.75a5.995 5.995 0 0 0-5.058 2.772m0 0a3 3 0 0 0-4.681 2.72 8.986 8.986 0 0 0 3.74.477m.94-3.197a5.971 5.971 0 0 0-.94 3.197M15 6.75a3 3 0 1 1-6 0 3 3 0 0 1 6 0Zm6 3a2.25 2.25 0 1 1-4.5 0 2.25 2.25 0 0 1 4.5 0Zm-13.5 0a2.25 2.25 0 1 1-4.5 0 2.25 2.25 0 0 1 4.5 0Z" />
</svg>
<h4 class="text-white lg:text-3xl text-2xl text-center py-5">
  Clients <br>Worldwide
</h4>
<h4 class="text-7xl text-center text-gray-500 opacity-100">3</h4>
</div>

<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   number of app
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div>
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-12 mx-auto text-[#adff00]">
  <path stroke-linecap="round" stroke-linejoin="round" d="M10.5 1.5H8.25A2.25 2.25 0 0 0 6 3.75v16.5a2.25 2.25 0 0 0 2.25 2.25h7.5A2.25 2.25 0 0 0 18 20.25V3.75a2.25 2.25 0 0 0-2.25-2.25H13.5m-3 0V3h3V1.5m-3 0h3m-3 18.75h3" />
</svg>

<h4 class="text-white lg:text-3xl text-2xl text-center py-5">
  Mobile <br>Apps
</h4>
<h4 class="text-7xl text-center text-gray-500 opacity-100">5</h4>
</div>


<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   wins
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div>
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-12 mx-auto text-[#adff00]">
  <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 0 1 3 3h-15a3 3 0 0 1 3-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 0 1-.982-3.172M9.497 14.25a7.454 7.454 0 0 0 .981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 0 0 7.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 0 0 2.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 0 1 2.916.52 6.003 6.003 0 0 1-5.395 4.972m0 0a6.726 6.726 0 0 1-2.749 1.35m0 0a6.772 6.772 0 0 1-3.044 0" />
</svg>

<h4 class="text-white lg:text-3xl text-2xl text-center py-5">
  Awards <br>Won
</h4>
<h4 class="text-7xl text-center text-gray-500 opacity-100">2</h4>
</div>

<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   wins
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div>
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-12 mx-auto text-[#adff00]">
  <path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 0 0 8.716-6.747M12 21a9.004 9.004 0 0 1-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 0 1 7.843 4.582M12 3a8.997 8.997 0 0 0-7.843 4.582m15.686 0A11.953 11.953 0 0 1 12 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0 1 21 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0 1 12 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 0 1 3 12c0-1.605.42-3.113 1.157-4.418" />
</svg>



<h4 class="text-white lg:text-3xl text-2xl text-center py-5">
  Web <br>Development
  
</h4>
<h4 class="text-7xl text-center text-gray-500 opacity-100">20</h4>
</div>



</div>
    </section>

<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm about me mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
 <section class=" bg-white  py-16 mt-16 rounded-2xl lg:px-10 px-3" id="about">

<div class="grid lg:grid-cols-2 grid-rows-1 lg:gap-x-16 gap-y-10 ">
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm image mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
<div >
  <img :src="world" alt="my world image" class="w-full h-full rounded-2xl object-cover">
</div>
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm about me texts mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
 <div>
  <h4 class="text-[#b4ff3c] font-bold  text-2xl">ABOUT ME</h4>
  <h4 class="lg:text-5xl text-4xl font-bold">Frontend Developer From Ghana</h4>
  <br>
  <p class="text-lg text-neutral-400">
    I'm a self-taught developer with expertise in Flutter, Vue, and .NET.
    My programming journey began in 2020, fueled by curiosity and a love for problem-solving.

  </p><br>
  <p class="text-lg text-neutral-400">
 With a background as a senior high school graduate, I continuously push myself to learn and grow.
I’m dedicated to building meaningful projects and delivering impactful solutions.


  </p>
 
  <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm important notes didsplay in flex  mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
   <div class="flex pt-6 space-x-12 lg:space-x-24">
<ul>
  <li class="text-xl font-bold">Name</li>
  <li class="text-gray-500 text-lg">John Bonnah</li>
  
  <li class="text-xl font-bold pt-3">Email</li>
  <li class="text-gray-500 text-lg"><a class="text-lg text-gray-500" href="mailto:www.bonnahpoku@gmail.com">Bonnahpoku@gmail.com</a></li>
  <li class="text-xl font-bold pt-3">Phone</li>
  <li class="text-gray-500 text-lg"><a class="text-lg text-gray-500" href="tel:+233554308135">0554308135</a></li>
</ul>

<ul>
  <li class="text-xl font-bold">Age</li>
  <li class="text-gray-500 text-lg">34</li>
  
  <li class="text-xl font-bold pt-3">Education</li>
  <li class="text-gray-500 text-lg">General Arts</li>
  <li class="text-xl font-bold pt-3">Freelance</li>
  <li class="text-gray-500 text-lg">Available</li>
</ul>
   </div><br><br>
   <button class="bg-[#adff00] hover:bg-opacity-50 hover:text-white px-10 py-3 font-bold text-lg rounded-lg">DWONLOAD  CV</button>
</div>
</div>

 </section>

 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm about me mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
  <section class=" bg-[#1e1f24]  py-12 mt-16 rounded-2xl lg:px-10 px-5">
<div class="grid lg:grid-cols-2 grid-rows-1 lg:gap-x-16 gap-y-10 ">
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   skills text
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div>
      <h4 class="text-[#b4ff3c] font-bold  text-xl">MY SKILLS</h4>
      <h4 class="lg:text-5xl text-4xl font-semibold text-white">I'm great in what I do  and loving it.</h4>
      <br>
      <br>
      <p class="text-lg text-neutral-400 whitespace-pre-wrap">
    Bring expertise and dedication to every project, ensuring high-quality results.
    Committed to continuous improvement, I deliver solutions that meet diverse needs.
  </p>
    </div>
     <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   skills bars
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div class="pt-7">

       <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   first bar
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->

      <ol class="flex justify-between pb-1">
        <li class="text-white font-bold">HTML5</li>
        <li class="text-[#adff00]">90%</li>
      </ol>
      <div class="bg-white relative max-w-[100%] h-3 rounded-full ">
  <div class="bg-[#adff00] w-[90%]  h-3 absolute rounded-full">
  </div>
    </div>
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   second bar
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <ol class="flex justify-between pb-1 mt-5">
        <li class="text-white font-bold">CSS3</li>
        <li class="text-[#adff00]">40%</li>
      </ol>
      <div class="bg-white relative max-w-[100%] h-3 rounded-full ">
  <div class="bg-[#adff00] w-[40%]  h-3 absolute rounded-full">
  </div>
    </div>

 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   third bar
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <ol class="flex justify-between pb-1 mt-5">
        <li class="text-white font-bold">FLUTTER</li>
        <li class="text-[#adff00]">60%</li>
      </ol>
      <div class="bg-white relative max-w-[100%] h-3 rounded-full ">
  <div class="bg-[#adff00] w-[60%]  h-3 absolute rounded-full">
  </div>
    </div>

 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   fourth bar
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <ol class="flex justify-between pb-1 mt-5">
        <li class="text-white font-bold">VUE</li>
        <li class="text-[#adff00]">40%</li>
      </ol>
      <div class="bg-white relative max-w-[100%] h-3 rounded-full ">
  <div class="bg-[#adff00] w-[40%]  h-3 absolute rounded-full">
  </div>
    </div>


    </div>
</div>
  </section>

   <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   portfolio
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
<section class=" bg-white  py-14 mt-16 rounded-2xl lg:px-10 px-5">
  <h5 class="font-extrabold text-2xl text-center underline decoration-[#adff00] decoration-2">PORTFOLIO</h5>
<br>
<p class="text-lg text-neutral-400 text-center lg:block  hidden">
  Showcasing a collection of work that demonstrates expertise and attention to detail.<br>
  Every project is crafted  to deliver quality and drive impactful results.
 </p>
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   for mobile only
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
 <p class="text-lg text-neutral-400 text-center lg:hidden block">
  Showcasing a collection of work that demonstrates expertise and attention to detail.
  Every project is crafted  to deliver quality and drive impactful results.
 </p>

 
   <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   tabs button
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div class="flex justify-center space-x-6 mt-7">
<button class="text-xl text-black border-gray-400 px-4 py-2 rounded-xl border  "
 v-for="tab in tabs" :key="tab"  :class="{'bg-[#adff00]':activeTab===tab,'text-gray-400':activeTab!==tab}" @click="activeTab=tab">{{ tab }}</button>

    </div>
     <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
   tabs contenton
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div class="pt-12">
      <div v-if="activeTab==='All'">
 <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      All
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div class="grid lg:grid-cols-3  lg:gap-x-6 gap-y-8">
<img :src="first" alt="first image of the tab" class="w-full h-full rounded-2xl">
<img :src="second" alt="second image of the tab" class="w-full h-full rounded-2xl">
<img :src="third" alt="third image of the tab" class="w-full h-full rounded-2xl">
<img :src="four" alt="four image of the tab" class="w-full h-full rounded-2xl">
<img :src="fifth" alt="fifth image of the tab" class="w-full h-full rounded-2xl">
<img :src="six" alt="six image of the tab" class="w-full h-full rounded-2xl">
    </div>
      </div>
      <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
        website
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
      <div v-if="activeTab==='Website'">
        <div class="grid lg:grid-cols-3  lg:gap-x-6 gap-y-8">

<img :src="second" alt="first image of the tab" class="w-full h-full rounded-2xl">


<img :src="fifth" alt="second image of the tab" class="w-full h-full rounded-2xl">
<img :src="six" alt="third image of the tab" class="w-full h-full rounded-2xl">
    </div>
      </div>
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      mobile
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
      <div v-if="activeTab==='Mobile '">
        <div class="grid lg:grid-cols-3  lg:gap-x-6 gap-y-8">

<img :src="four" alt="first image of the tab" class="w-full h-full rounded-2xl">


<img :src="first" alt="second image of the tab" class="w-full h-full rounded-2xl">
<img :src="third" alt="third image of the tab" class="w-full h-full rounded-2xl">
    </div>
      </div>

    </div>
</section>

<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      service
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <section  class=" bg-[#1e1f24]  py-12 mt-16 rounded-2xl lg:px-10 px-5">
      <h5 class="font-bold text-2xl text-center underline decoration-[#adff00] decoration-2 text-white">SERVICE</h5>
<br><p class="text-lg text-neutral-400 text-center">
  We strive for excellence in delivering outstanding results that truly stand out.
</p>

 <div class="grid lg:grid-cols-3 pt-16 lg:gap-x-6 gap-y-8">
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      service (mobile apps)
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
<div class="border border-gray-700 rounded-2xl py-10 px-2">

<div class="w-24 h-24  bg-gray-700 bg-opacity-30 rounded-full relative mx-auto ">
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 mx-auto text-[#adff00] absolute top-7 start-8">
  <path stroke-linecap="round" stroke-linejoin="round" d="M10.5 1.5H8.25A2.25 2.25 0 0 0 6 3.75v16.5a2.25 2.25 0 0 0 2.25 2.25h7.5A2.25 2.25 0 0 0 18 20.25V3.75a2.25 2.25 0 0 0-2.25-2.25H13.5m-3 0V3h3V1.5m-3 0h3m-3 18.75h3" />
</svg>

</div>
<h5 class="text-3xl text-center py-8 text-white">Mobile Apps</h5>
<p class="text-center text-lg text-neutral-400">
  Building apps that bring ideas to life and deliver seamless user experiences,
  crafted with precision and built to perform reliably across all devices.
</p>
</div>


<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      service (website)
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div class="border border-gray-700 rounded-2xl py-10 px-1">

<div class="w-24 h-24  bg-gray-700 bg-opacity-30 rounded-full relative mx-auto ">
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 mx-auto text-[#adff00] absolute top-7 start-8">
  <path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 0 0 8.716-6.747M12 21a9.004 9.004 0 0 1-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 0 1 7.843 4.582M12 3a8.997 8.997 0 0 0-7.843 4.582m15.686 0A11.953 11.953 0 0 1 12 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0 1 21 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0 1 12 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 0 1 3 12c0-1.605.42-3.113 1.157-4.418" />
</svg>

</div>
<h5 class="text-3xl text-center py-8 text-white">Web Development</h5>
<p class="text-center text-lg text-neutral-400">
  Creating dynamic websites that combine aesthetic appeal with top-notch functionality,
  ensuring a user-friendly experience that caters to your unique business needs.
</p>
</div>


<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      service (desktop)
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div class="border border-gray-700 rounded-2xl py-10 px-2">

<div class="w-24 h-24  bg-gray-700 bg-opacity-30 rounded-full relative mx-auto ">
 

<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 mx-auto text-[#adff00] absolute top-7 start-8">
  <path stroke-linecap="round" stroke-linejoin="round" d="M9 17.25v1.007a3 3 0 0 1-.879 2.122L7.5 21h9l-.621-.621A3 3 0 0 1 15 18.257V17.25m6-12V15a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 15V5.25m18 0A2.25 2.25 0 0 0 18.75 3H5.25A2.25 2.25 0 0 0 3 5.25m18 0V12a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 12V5.25" />
</svg>
</div>
<h5 class="text-3xl text-center py-8 text-white">Desktop Apps</h5>
<p class="text-center text-lg text-neutral-400">
  Developing robust desktop applications tailored to enhance productivity,
  designed to integrate smoothly and run efficiently on various platforms.
</p>
</div>
    </div>
    </section>

    <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      Testimonial
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
<TestimonialFile/>
    
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      contact us
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <section class=" bg-white  py-36 mt-16 rounded-2xl lg:px-10 px-5" id="hire">
      <h5 class="font-extrabold text-2xl text-center underline decoration-[#adff00] decoration-2">GET IN TOUCH</h5>
      <br>
      <p class="text-lg text-neutral-600 text-center lg:block hidden">
        Feel free to reach out with any questions or project ideas. I'm here to help bring your <br>  vision to life and make every interaction a meaningful one.
      </p>
      <p class="text-lg text-neutral-600 text-center lg:hidden block whitespace-break-spaces">
        Feel free to reach out with any questions or project ideas. I'm here to help bring your   vision to life and make every interaction a meaningful one.
      </p>
     
      <div class="grid lg:grid-cols-3 grid-rows-1 pt-12 lg:gap-x-5  gap-y-4">
    <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      address
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div>
      <div class="w-20 h-20  bg-[#adff00] rounded-full relative mx-auto ">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 mx-auto text-neutral-500 absolute top-6 start-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z" />
  <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z" />
</svg>

</div> <br>
<h5 class="text-2xl font-bold text-center">Address</h5>
<p class="text-lg text-neutral-500 text-center">Dumanafo. Plot 10 Blk K</p>
    </div>
       
  <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      phone
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div>
      <div class="w-20 h-20  bg-[#adff00] rounded-full relative mx-auto ">

        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 mx-auto text-neutral-500 absolute top-6 start-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 0 1-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 0 0-1.091-.852H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z" />
</svg>

</div> <br>
<h5 class="text-2xl font-bold text-center">Address</h5>
<p class="text-center"><a class="text-lg text-neutral-500" href="tel:+233554308135">0554308135</a></p>
    </div>

         
  <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      phone
    mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div>
      <div class="w-20 h-20  bg-[#adff00] rounded-full relative mx-auto ">

        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-8 mx-auto text-neutral-500 absolute top-6 start-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 9v.906a2.25 2.25 0 0 1-1.183 1.981l-6.478 3.488M2.25 9v.906a2.25 2.25 0 0 0 1.183 1.981l6.478 3.488m8.839 2.51-4.66-2.51m0 0-1.023-.55a2.25 2.25 0 0 0-2.134 0l-1.022.55m0 0-4.661 2.51m16.5 1.615a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V8.844a2.25 2.25 0 0 1 1.183-1.981l7.5-4.039a2.25 2.25 0 0 1 2.134 0l7.5 4.039a2.25 2.25 0 0 1 1.183 1.98V19.5Z" />
</svg>

</div> <br>
<h5 class="text-2xl font-bold text-center">Email</h5>
<p class="text-center"><a class="text-lg text-neutral-500" href="mailto:www.bonnahpoku@gmail.com">Bonnahpoku@gmail.com</a></p>
    </div>

      </div>

      <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
      the two grid  for the contact us
      mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
      <div class="grid lg:grid-cols-2 grid-rows-1 lg:gap-x-8 gap-y-8 pt-16">
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
     the map
      mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
<div class=" h-full w-full rounded-2xl">
  <iframe src="https://www.google.com/maps/embed?pb=!1m17!1m11!1m3!1d102122218.44251117!2d-78.87664549542814!3d38.63685821932477!2m2!1f0!2f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xfdbbf9d75456329%3A0x4677e0670ea1d98b!2sWadie%20Adwumakase!5e0!3m2!1sen!2sgh!4v1730148990461!5m2!1sen!2sgh"  style="border:0;" class="w-full h-full" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>
<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
     the contact us form
      mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <div>
      <form >
        <h6 class="text-4xl font-bold">Write a message</h6>
        <div class="grid lg:grid-cols-2 grid-rows-1 lg:gap-x-5  gap-y-4 pt-10">
          <input type="text" placeholder="Name*" class="border border-gray-400 rounded-md p-3">
          <input type="email" placeholder="Email*" class="border border-gray-400 rounded-md p-3">
        </div>
        <textarea   class="border border-gray-400 rounded-md mt-5 w-full h-[70%] p-4 mb-3" placeholder="Your Message here" rows="8"></textarea>
    
        <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
     submit button
      mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
        <button class="bg-[#adff00] hover:bg-opacity-50 hover:text-white px-10 py-3 font-bold text-lg rounded-lg">SEND MESSAGE</button>
      </form>
    </div>
      </div>
    </section>

<!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
     footer
      mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
    <section class=" bg-[#1e1f24]  py-16 mt-16 rounded-2xl lg:px-10 px-5">
      <h6 class="text-[#adff00] text-4xl font-bold text-center">Tenace</h6> <br>
      <p class="text-center text-lg text-neutral-500 lg:block hidden">
        Driven by a deep commitment, I strive to overcome challenges and approach each task with resilience.
         <br> I believe persistence and focus lead to the best results, turning obstacles into growth opportunities.</p>
        <!-- mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
     for mobile only
      mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm -->
         <p class="text-center text-lg text-neutral-500 block lg:hidden whitespace-break-spaces">
        Driven by a deep commitment, I strive to overcome challenges and approach each task with resilience.
          I believe persistence and focus lead to the best results, turning obstacles into growth opportunities.</p>
        </section>
    <footer class="pt-6">
      <div class="flex justify-between gap-3">
        <p class="text-lg text-neutral-500">All rights reserved &copy; 2024 <strong class="font-bold">Tenace TechZone</strong></p>
     <p class="text-lg text-neutral-500">Terms & Condition <span>Privacy Policy</span></p>
      </div>
      
    </footer>
    </main>
</template>

<script>
import image from '@/assets/images/hero.jpg'
import world from '@/assets/images/world.jpg'
//  mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
//       portfolio images
//     mmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm 
import first from '@/assets/images/fir.jpg'
import second from '@/assets/images/sec.jpg'
import third from '@/assets/images/thi.jpg'
import four from '@/assets/images/fou.jpg'
import fifth from '@/assets/images/fiv.jpg'
import six from '@/assets/images/six.jpg'
// mmmmmmmmmmmmmmmmmmmm
// file imports 
//mmmmmmmmmmmmm
import TestimonialFile from '@/views/TestimonialFile.vue'
export default {
components:{
TestimonialFile
},
  data() {
    return{
      image,
      world,
      first,second,third,four,fifth,six,
      isScroll:false,
activeTab:'All',
tabs:['All','Website','Mobile ']
    }
  },
  mounted(){
window.addEventListener('scroll',this.handleScroll)
  },
  beforeUnmount(){
    window.removeEventListener('scroll',this.handleScroll)
  },
  methods:{
    handleScroll(){
      this.isScroll=window.scrollY>20
    }
  }
}
</script>