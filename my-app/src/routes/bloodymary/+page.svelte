
<div class="flex flex-col items-center relative">
    <img class="w-[10vw] py-10 relative z-10 " src="/images/fangs.png" alt="BotBlast Logo" id= "logo">
    <div>
        <p class="pt-10 text-white text-7xl tracking-tight text-center playwrite-at-regular" style="font-family: 'Playwrite AT', 'Arial Black', Arial, sans-serif;">
            What if vampires ate us?
        </p>
        <link href="https://fonts.googleapis.com/css2?family=Playwrite+AT:ital,wght@0,100..400;1,100..400&display=swap" rel="stylesheet">
    </div>
     
    <div class= "pt-10 w-[32vw] text-center">
        <p class="text-white" style="font-family: 'Playwrite AT', 'Arial Black', Arial, sans-serif;">A fast paced and intense game about cooking brains and humans to satisfy your vampire clients!</p>
        
    </div>
  
    
</div>

<div class="flex justify-center py-20">
       <!-- svelte-ignore a11y_media_has_caption -->
       <video 
                  src=/videos/BloodyMary_Cutscene.mov
                  playsinline
                  controls
                  volume="0.6"
                  class="w-full max-w-4xl rounded-lg"
                ></video>
</div>

<div class="flex justify-center pb-10">
    <button class="flex flex-row pr-10" style="background-image: url('/images/buttongrandeBM.png'); background-size: cover; background-position: center;">
        <a href="https://github.com/JommyV/BloodyMary" class="flex flex-row items-center gap-2">
            <p style="font-family: 'Bungee', 'Orbitron', 'Arial Black', Arial, sans-serif;" class=" pl-8 text-white">GitHub Repo</p>
            <img src="/images/github-logo.png" alt="GitHub Logo" class="max-w-8 py-2">
        </a>
    </button>


</div>
    
 
<footer id="contacts" class="left-0 right-0 pb-2">
    <div class="w-11/12 h-px bg-gray-400 mt-20 mb-5 mx-auto"></div> 
    <div class="flex justify-between flex-row items-center pl-[4%]">
        <p style="font-family: 'Bungee', 'Orbitron', 'Arial Black', Arial, sans-serif;" class="text-white flex flex-row items-center gap-2"> Made in GDScript with <img src="/images/logoGodot.png" alt="Godot Logo" class="max-w-20 "></p>
        
        <p class="text-white pr-[4%]">© 2026 Bloody Mary Team.</p>
    </div>
    <div>
        
    </div>
</footer>


<style>
    :global(body) {
         
        min-height: 100vh;
        margin: 0;
        background-image: url('/images/backgroundbm.png');
        background-size: cover;
        background-position: center;
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