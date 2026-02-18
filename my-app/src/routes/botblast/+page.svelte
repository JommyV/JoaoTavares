
<div class="flex flex-col items-center relative">
    <img 
        class="w-[20vw] fixed top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 -z-10" 
        src="/images/doc.png" 
        alt="BotBlast Doc" 
        style="filter: blur(2px); opacity: 0.7;" 
        id="doc"
        >


    <img class="w-[50vw] py-10 relative z-10 " src="/images/botblast.png" alt="BotBlast Logo" id= "logo">
    <div>
        <p class="pt-10 text-white text-7xl font-extrabold tracking-tight animate-pulse text-center" style="font-family: 'Bungee', 'Orbitron', 'Arial Black', Arial, sans-serif;">
            Gotta go Blast.
        </p>
        <link href="https://fonts.googleapis.com/css2?family=Bungee:wght@400&family=Orbitron:wght@700&display=swap" rel="stylesheet">
    </div>
     
    <div class= "pt-10 w-[32vw] text-center">
        <p class="text-white" style="font-family: 'Bungee', 'Orbitron', 'Arial Black', Arial, sans-serif;">It's simple, we blast and we go fast</p>
        
    </div>
  
    
</div>

<div class="flex justify-center py-20">
       <!-- svelte-ignore a11y_media_has_caption -->
       <video 
                  src=/videos/BBTrailer.mov
                  playsinline
                  controls
                  volume="0.6"
                  class="w-full max-w-4xl rounded-lg"
                ></video>
</div>

<div class="flex justify-center pb-10">
    <button class="flex flex-row pr-10" style="background-image: url('/images/ButtonBack.png'); background-size: cover; background-position: center;">
        <a href="https://github.com/JommyV/BotBlastDevelopment" class="flex flex-row items-center gap-2">
            <p style="font-family: 'Bungee', 'Orbitron', 'Arial Black', Arial, sans-serif;" class=" pl-5 text-white">GitHub Repo</p>
            <img src="/images/github-logo.png" alt="GitHub Logo" class="max-w-10">
        </a>
    </button>


</div>
    
 
<footer id="contacts" class="left-0 right-0 pb-2">
    <div class="w-11/12 h-px bg-gray-400 mt-20 mb-5 mx-auto"></div> 
    <div class="flex justify-between flex-row items-center pl-[4%]">
        <p style="font-family: 'Bungee', 'Orbitron', 'Arial Black', Arial, sans-serif;" class="text-white flex flex-row items-center"> Made in C++ with <img src="/images/UELogo.png" alt="Unreal Engine Logo" class="max-w-10 "></p>
        
        <p class="text-white pr-[4%]">© 2026 BotBlast Team. Gotta Go Blast.</p>
    </div>
    <div>
        
    </div>
</footer>


<style>
    :global(body) {
         
        min-height: 100vh;
        margin: 0;
        background-color: rgb(27, 25, 25);
    }
        
    :global(.animate-ping-slow) {
            animation: ping 3s cubic-bezier(0, 0, 0.2, 1) infinite;
            animation-iteration-count: 1;
        }
        @keyframes ping {
            75%, 100% {
                transform: scale(2);
                opacity: 0;
            }
        }
</style>