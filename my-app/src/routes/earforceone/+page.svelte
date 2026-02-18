
<div class="flex flex-col items-center relative">
    <img 
        class="w-[20vw] fixed top-1/2 left-1/4 -translate-x-1/2 -translate-y-1/2 -z-10" 
        src="/images/fbi1_sprite.png" 
        alt="Fbi Sprite" 
        style="filter: blur(2px); opacity: 0.7;" 
        id="doc"
        >
        <img 
        class="w-[20vw] fixed top-1/2 left-3/4 -translate-x-1/2 -translate-y-1/2 -z-10" 
        src="/images/fbi1_sprite.png" 
        alt="Fbi Sprite" 
        style="filter: blur(2px); opacity: 0.7;" 
        id="doc"
        >
        <img 
        class="w-[20vw] fixed top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 -z-10" 
        src="/images/trump_stand.png" 
        alt="Fbi Sprite" 
        style="filter: blur(2px); opacity: 1;" 
        id="doc"
        >
        <img 
        class="w-[20vw] fixed top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 -z-11" 
        src="/images/trump_normal.png" 
        alt="Fbi Sprite" 
        style="filter: blur(2px); opacity: 0.7;" 
        id="doc"
        >
    
        


    <img class="w-[50vw] py-10 relative z-10 -translate-x-10" src="/images/ear.png" alt="EarForceOne Logo" id="logo">
    <div>
        <p class="pt-10 text-black text-7xl font-extrabold tracking-tight animate-pulse text-center" style="font-family: 'Pixelify Sans';">
            GET DOWN MISTER PRESIDENT!
        </p>

        <link href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@400..700&display=swap" rel="stylesheet">
    </div>
     
    <div class= "pt-10 w-[48vw] text-center">
        <p class="text-black text-xl" style="font-family: 'Pixelify Sans', sans-serif;">Can you save the presidents ears and life from a barrage of shots?</p>
        <p class="text-black text-xl" style="font-family: 'Pixelify Sans', sans-serif;">A very simple one-mechanic newsgame designed around the events of 2024.</p>
        
    </div>
  
    
</div>

<div class="flex justify-center py-20">
       <!-- svelte-ignore a11y_media_has_caption -->
       <video 
                  src=/videos/TrumpShowCase.mp4
                  playsinline
                  controls
                  volume="1"
                  class="w-full max-w-4xl rounded-lg"
                ></video>
</div>

<div class="flex justify-center pb-10">
    <button class="flex flex-row pr-5 rounded-full cursor-pointer items-center gap-2" style="background-image: url('/images/Button_trump.png'); background-size: cover; background-position: center;" on:click={() => window.open('https://github.com/JommyV/Trump-Simulator', '_blank')}>
       
            <p style="font-family: 'Pixelify Sans', sans-serif;" class=" pl-4 text-white">GitHub Repo</p>
            <img src="/images/github-white-icon.png" alt="GitHub Logo" class="max-w-10">
      
    </button>
</div>


 
<footer id="info" class="left-0 right-0 pb-2">
    <div class="w-11/12 h-px bg-gray-400 mt-20 mb-5 mx-auto"></div> 
    <div class="flex justify-between flex-row items-center pl-[4%]">
        <p style="font-family: 'Bungee', 'Orbitron', 'Arial Black', Arial, sans-serif;" class="text-white flex flex-row items-center gap-1"> Made in C# with <img src="/images/unity_logo.png" alt="Unreal Engine Logo" class="max-w-10"></p>
        
     

        <p class="text-white pr-[4%]">© 2024</p>
    </div>
    <div>
        
    </div>
</footer>


<style>
    :global(body) {
         
        min-height: 100vh;
        margin: 0;
        background-color: rgb(27, 25, 25);
        background-image: url('/images/clouds.png');
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