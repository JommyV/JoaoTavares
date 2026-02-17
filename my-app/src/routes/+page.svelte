

<script>
  import { fade } from 'svelte/transition';
    import TwoChoiceGame from '../lib/options.svelte';
    import { gameStarted } from '$lib/stores.js';

</script>
  
<header class="flex flex-row justify-between items-center p-4 text-Black w-11/12 gap-10">
    <div class="flex flex-row items-center gap-2 pl-10">
        <div class="w-5 h-5 rounded-full bg-blue-300 drop-shadow-lg"></div>
        <div class="flex flex-row gap-2 items-center" style="font-family: 'Montserrat', sans-serif;">
            <h1 class="font-bold">João Miguel Tavares</h1>
            <p class="text-xs"> VideoGame Programmer
            </p>
        </div>
    </div>
    <div class="flex flex-row gap-4 items-center">
        <button>Resume</button>
        <div class="w-px h-6 bg-gray-400"></div>
        <button>Projetos</button>
        <div class="w-px h-6 bg-gray-400"></div>
        <button>Contacts</button>
        <div class="w-px h-6 bg-gray-400"></div>
        <button class="md: pr-5 sm: pr-5">Personal</button>
    </div>
</header>

<div id="main info" class="flex justify-center-safe  md:justify-center">

    <div class="flex flex-row items-center pt-10">
        <div class= "px-4">
            <img src="/images/jaozin.jpg" alt="João Tavares" class="w-full max-w-80 min-w-50 rounded-full drop-shadow-lg"> 
        </div>
        <div >
        <h1
        class="text-left text-2xl lg:text-5xl font-extrabold bg-clip-text bg-gradient-to-r from-white via-gray to-white drop-shadow-lg pb-4 break-words whitespace-normal "
            >
        João Tavares
        </h1>
        <h2 class="text-left text-md sm:text-lg md:text-xl lg:text-2xl font-bold tracking-wide bg-clip-text bg-gradient-to-r from-white via-gray to-white drop-shadow-lg pb-4 break-words whitespace-normal" style="font-family: 'Montserrat'">
                    About me
        </h2>  
        <p class="text-xl text-justify max-w-md" style="font-family: Montserrat, sans-serif;">
                            Programmer and Game Designer with a passion for creating unique and engaging gaming experiences both in digital as well as physical formats. 
                        </p>  </div>  
        
        <link href="https://fonts.googleapis.com/css2?family=Borel&family=Jaini&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Roboto:ital,wght@0,900;1,900&display=swap" rel="stylesheet">
        
    </div>  
</div>
<section id = "info">       
    <div id="projects" class="flex justify-evenly items-center sm:items-left w-half px-4 max-w-screen-lg mx-auto gap-5 pl-70">    
        <div class="flex sm:flex-row flex-col gap-5 justify-center items-center">
            <div class="flex items-center justify-center w-20 h-20 rounded-full bg-gray-100 drop-shadow-lg hover:bg-gray-300 rounded-full transition-colors">
                <button on:click={() => window.open('/botblast', '_blank')}>
                                <img src="/images/doc.png" alt="João Tavares" class="w-16 h-16 rounded-full object-cover">
                </button>
            </div>  
           <div class="flex items-center justify-center w-20 h-20 rounded-full bg-gray-100 drop-shadow-lg hover:bg-gray-300 rounded-full transition-colors" >
                <button on:click={() => window.open('/bloodymary', '_blank')}>
                    <img src="/images/fangs.png" alt="João Tavares" class="w-14 h-14">
            </div> 
            <div class="flex items-center justify-center w-20 h-20 rounded-full bg-gray-100 drop-shadow-lg hover:bg-gray-300 rounded-full transition-colors">
                <button on:click={() => window.open('/jumpyufo', '_blank')}>
                    <img src="/images/jumpy.jpeg" alt="João Tavares" class="w-16 h-16 rounded-full object-cover">
            </div> 
             <div class="flex items-center justify-center w-20 h-20 rounded-full bg-gray-100 drop-shadow-lg hover:bg-gray-300 rounded-full transition-colors">
                <button on:click={() => window.open('/earforceone', '_blank')}>
                    <img src="/images/ear.png" alt="João Tavares" class="w-16 h-10 ">
            </div> 
        </div>

    </div>   
</section>

    
<footer id="contacts" class="fixed bottom-0 left-0 right-0">
    <div class="w-11/12 h-px bg-gray-400 mt-20 mb-5 mx-auto"></div>  

    <div class="flex flex-row flex-wrap justify-between w-11/12 mx-auto">
        <div>
            <h1 class="text-left sm:text-1xl md:text-sm lg:text-lg font-bold bg-clip-text" style="font-family: Montserrat, sans-serif;">Email</h1>
            <h2 class="pb-10" style="font-family: Montserrat, sans-serif;">tavaresjmv@gmail.com</h2>
        </div>
        <div>
            <h1 class="text-left sm:text-1xl md:text-sm lg:text-lg font-bold bg-clip-text" style="font-family: Montserrat, sans-serif;">GitHub</h1>
            <a href="https://github.com/JommyV" class="pb-10 text-blue-500 hover:underline" style="font-family: Montserrat, sans-serif;">https://github.com/JommyV</a>
        </div>
        <div>
           <h1 class="text-left sm:text-1xl md:text-sm lg:text-lg font-bold bg-clip-text" style="font-family: Montserrat, sans-serif;">Linkedin</h1>
            <a href="https://www.linkedin.com/in/joao-miguel-tavares/" class="pb-10 text-blue-500 hover:underline" style="font-family: Montserrat, sans-serif;">https://www.linkedin.com/in/joao-miguel-tavares/</a>
        </div>

    </div>
</footer>

<!-- <p class="text-white text-right ">
    This is a sentence with a footnote.<sup><a href="#footnote-1" class="text-blue-400 hover:underline justify-right">[1]</a></sup>
  </p> -->




<style>
    .Letter {
        font-family: "Roboto", sans-serif;
        font-optical-sizing: auto;
        font-weight: 900;
        font-style: normal;
        font-variation-settings:
        "wdth" 100;
    }
    
    
    
    :global(body) {
        min-height: 100vh;
        margin: 0;
        background: #ffffff;
    }

    
    :global(body) {
         
        min-height: 100vh;
        margin: 0;
    }
        
    :global(.animate-ping-slow) {
            animation: ping 1s cubic-bezier(0, 0, 0.2, 1) infinite;
            animation-iteration-count: 3;
            
        }
        @keyframes ping {
            50% {
                transform: scale(1.5);
                opacity: 0;
            }
            100% {
                transform: scale(1);
                opacity: 1;
            }
        }

</style>