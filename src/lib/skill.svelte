<script>
  import { fade, slide, scale } from "svelte/transition";
  import Saos from "saos";
</script>

<section class=" mx-2 md:max-w-full">
  <!--heading-->
  <h1 class=" text-center text-4xl p-5 font-bold ">My Skills</h1>

  <Saos animation={"from-left 1s cubic-bezier(0.35, 0.5, 0.65, 0.95) both"}>
    <div class="flex items-stretch justify-around">
      <div
        class=" container grid grid-cols-3 gap-6  md:grid-cols-4 transition:fade "
      >
        <div
          class=" h-50 w-50 border-t-4 border-orange-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
       "
        >
          <img
            src="../../img/php-programming-language.svg"
            class="h-14 w-14 pt-2"
            alt=""
          />
          <h4 class=" text-center text-1xl p-1   ">PHP</h4>
        </div>

        <div
          class="h-50 w-50 border-t-4 border-blue-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
     "
        >
          <img
            src="../../img/cpanel-svgrepo-com.svg"
            class="h-14 w-14 pt-2"
            alt=""
          />
          <h4 class=" text-center text-1xl p-1   ">CPANEL</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-green-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >
          <img
            src="../../img/javascript-programming-language.svg"
            class="h-14 w-14 pt-2"
            alt=""
          />
          <h4 class=" text-center text-1xl p-1   ">JAVASCRIPT</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-purple-400  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >
          <img
            src="../../img/typescript-svgrepo-com.svg"
            class="h-14 w-14 pt-2"
            alt=""
          />
          <h4 class=" text-center text-1xl p-1   ">TypeScript</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-purple-400  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >
          <img src="../../img/mysql.svg" class="h-14 w-14 pt-2" alt="" />
          <h4 class=" text-center text-1xl p-1   ">SQL DATABASE</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-green-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >
          <img src="../../img/svelte.svg" class="h-14 w-14 pt-2" alt="" />
          <h4 class=" text-center text-1xl p-1   ">SVELTEKIT</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-blue-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >
          <img src="../../img/tailwind-css.svg" class="h-14 w-14 pt-2" alt="" />
          <h4 class=" text-center text-1xl p-1   ">TAILWINDCSS</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-orange-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >
          <img
            src="../../img/wordpress-color-svgrepo-com.svg"
            class="h-14 w-14 pt-2"
            alt=""
          />
          <h4 class=" text-center text-1xl p-1   ">WORDPRESS</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-blue-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >

        <img
        src="../../img/node-js-svgrepo-com.svg"
        class="h-14 w-14 pt-2"
        alt=""
      />
      <h4 class=" text-center text-1xl p-1   ">NODE JS</h4>
    </div>

    <div
      class=" h-50 w-50 border-t-4 border-blue-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
"
    >
          <img
            src="../../img/php-programming-language.svg"
            class="h-14 w-14 pt-2"
            alt=""
          />
          <h4 class=" text-center text-1xl p-1   ">CODEIGNITER</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-orange-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >
          <img
            src="../../img/bootstrap-5-logo.svg"
            class="h-14 w-14 pt-2"
            alt=""
          />
          <h4 class=" text-center text-1xl p-1   ">BOOTSTRAP</h4>
        </div>

        <div
          class=" h-50 w-50 border-t-4 border-green-500  flex flex-col items-center justify-center transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 hover:font-bold
   "
        >
          <img src="../../img/jquery.svg" class="h-14 w-14 pt-2" alt="" />
          <h4 class=" text-center text-1xl p-1   ">JQUERY</h4>
        </div>
      </div>
    </div>
  </Saos>
</section>

<style>
  @keyframes -global-from-left {
    0% {
      transform: rotateX(50deg) translateX(-200vw) skewX(-50deg);
      opacity: 1;
    }
    100% {
      transform: rotateX(0deg) translateX(0) skewX(0deg);
      opacity: 1;
    }
  }

  /* ----------------------------------------------
 * Animations below by Animista on 2020-7-11
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info. 
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

  @keyframes -global-scale-in-center {
    0% {
      transform: scale(0);
      opacity: 1;
    }
    100% {
      transform: scale(1);
      opacity: 1;
    }
  }

  @keyframes -global-rotate-in-center {
    0% {
      transform: rotate(-360deg);
      opacity: 0;
    }
    100% {
      transform: rotate(0);
      opacity: 1;
    }
  }

  @keyframes -global-slide-in-top {
    0% {
      transform: translateY(-1000px);
      opacity: 0;
    }
    100% {
      transform: translateY(0);
      opacity: 1;
    }
  }

  @keyframes -global-slide-in-fwd-tr {
    0% {
      transform: translateZ(-1200px) translateY(-700px) translateX(500px);
      opacity: 0;
    }
    100% {
      transform: translateZ(0) translateY(0) translateX(0);
      opacity: 1;
    }
  }

  @keyframes -global-slide-in-elliptic-top-fwd {
    0% {
      transform: translateY(-600px) rotateX(-30deg) scale(0);
      transform-origin: 50% 100%;
      opacity: 0;
    }
    100% {
      transform: translateY(0) rotateX(0) scale(1);
      transform-origin: 50% 1400px;
      opacity: 1;
    }
  }

  @keyframes -global-roll-in-left {
    0% {
      transform: translateX(-800px) rotate(-540deg);
      opacity: 0;
    }
    100% {
      transform: translateX(0) rotate(0deg);
      opacity: 1;
    }
  }

  @keyframes -global-roll-in-blurred-left {
    0% {
      transform: translateX(-1000px) rotate(-720deg);
      filter: blur(50px);
      opacity: 0;
    }
    100% {
      transform: translateX(0) rotate(0deg);
      filter: blur(0);
      opacity: 1;
    }
  }

  @keyframes -global-tilt-in-fwd-tr {
    0% {
      transform: rotateY(20deg) rotateX(35deg) translate(300px, -300px)
        skew(-35deg, 10deg);
      opacity: 0;
    }
    100% {
      transform: rotateY(0) rotateX(0deg) translate(0, 0) skew(0deg, 0deg);
      opacity: 1;
    }
  }

  @keyframes -global-swing-in-top-fwd {
    0% {
      transform: rotateX(-100deg);
      transform-origin: top;
      opacity: 0;
    }
    100% {
      transform: rotateX(0deg);
      transform-origin: top;
      opacity: 1;
    }
  }

  @keyframes -global-puff-in-center {
    0% {
      transform: scale(2);
      filter: blur(4px);
      opacity: 0;
    }
    100% {
      transform: scale(1);
      filter: blur(0px);
      opacity: 1;
    }
  }

  @keyframes -global-fade-in {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }

  /* EXITS */
  @keyframes -global-scale-out-center {
    0% {
      transform: scale(1);
      opacity: 1;
    }
    100% {
      transform: scale(0);
      opacity: 1;
    }
  }

  @keyframes -global-rotate-out-center {
    0% {
      transform: rotate(0);
      opacity: 1;
    }
    100% {
      transform: rotate(-360deg);
      opacity: 0;
    }
  }

  @keyframes -global-rotate-out-2-cw {
    0% {
      transform: rotate(0);
      opacity: 1;
    }
    100% {
      transform: rotate(45deg);
      opacity: 0;
    }
  }

  @keyframes -global-swirl-out-bck {
    0% {
      transform: rotate(0) scale(1);
      opacity: 1;
    }
    100% {
      transform: rotate(-540deg) scale(0);
      opacity: 0;
    }
  }

  @keyframes -global-flip-out-hor-top {
    0% {
      transform: rotateX(0);
      opacity: 1;
    }
    100% {
      transform: rotateX(70deg);
      opacity: 0;
    }
  }

  @keyframes -global-slide-out-top {
    0% {
      transform: translateY(0);
      opacity: 1;
    }
    100% {
      transform: translateY(-1000px);
      opacity: 0;
    }
  }

  @keyframes -global-slide-out-fwd-center {
    0% {
      transform: translateZ(1);
      opacity: 1;
    }
    100% {
      transform: translateZ(600px);
      opacity: 0;
    }
  }

  @keyframes -global-slide-out-elliptic-top-bck {
    0% {
      transform: translateY(0) rotateX(0) scale(1);
      transform-origin: 50% 1400px;
      opacity: 1;
    }
    100% {
      transform: translateY(-600px) rotateX(-30deg) scale(0);
      transform-origin: 50% 100%;
      opacity: 1;
    }
  }
</style>
