
<template>
    <section class="relative h-screen flex flex-col text-white top-0">
     <ClientOnly> 
     <video-background 
         id="myVideo"
         src="/video/V09-0001-0500.mp4"
         poster="/images/prev1.jpg"
         overlay="linear-gradient(to right, zinc-900, slate-900)"
         class="fixed top-0 left-0 w-full h-full overflow-hidden mt-5">
         <h1 class="font-extrabold text-6xl container pt-10">This page illustrates the use of video with TailwindCSS.
        </h1>
        <h3 class="font-bold text-xl container">The video in the back is a loop of 250 frames saved as an mp4 file.
        </h3>   
        </video-background>
    </ClientOnly>  
   </section>>
</template>
