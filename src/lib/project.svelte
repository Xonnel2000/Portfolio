<script>
  import { fade, slide, scale } from "svelte/transition";
  import Saos from "saos";
</script>

<section class="mb-6">
  <!--heading-->
  <h1 class=" text-center text-4xl p-5 font-bold ">My project</h1>

  <Saos animation={"from-left 1s cubic-bezier(0.35, 0.5, 0.65, 0.95) both"}>
    <div class="flex justify-center md:mx-auto">
      <div
        class=" container  grid grid-cols-1 gap-6  md:grid-cols-3 place-items-center md:mx-auto relative"
      >
        <div class=" h-90 w-80 border-t-4 border-blue-500   ">
          <img src="../../img/Untitled11.png" alt="" />
          <h2 class=" text-left text-2xl p-1 font-bold  ">
            Office Of The President
          </h2>
          <p class="p-2">
            An online registration and monitoring system used to monitor and
            rate the performace of goverment ministries and departments.
          </p>
        </div>

        <div class=" h-90 w-80 border-t-4 border-orange-500   ">
          <img src="../../img/Untitled33.png" alt="" />
          <h2 class=" text-left text-2xl p-1 font-bold  ">
            MMTU Students Registration
          </h2>
          <p class="p-2">
            An online student registration system for MMTU with print
            functionality and Short Messaging System(SMS) for student.
          </p>
        </div>

        <div class=" h-90 w-80 border-t-4 border-purple-500   ">
          <img src="../../img/Untitledportal.png" alt="" />
          <h2 class=" text-left text-2xl p-1 font-bold  ">
            MMTU Students Portal
          </h2>
          <p class="p-2">
            An online system that contain full university management system like
            hotel, library assignment, HR,registra,fees,check result,generate
            report and check reference of Milton Maigai Techincal University
          </p>
        </div>

        <div class=" h-90 w-80 border-t-4 border-amber-500   ">
          <img src="../../img/Untitled23.png" alt="" />
          <h2 class=" text-left text-2xl p-1 font-bold  ">
            Local Goverment Website
          </h2>
          <p class="p-2">
            Ministry of Local Goverment offical website with email, local and
            online facilities
          </p>
        </div>

        <div class=" h-90 w-80 border-t-4 border-green-500   ">
          <img src="../../img/Untitledmfmr.png" alt="" />
          <h2 class=" text-left text-2xl p-1 font-bold  ">
            Fishery and Marine Resouces
          </h2>
          <p class="p-2">
            Ministry of Marine Resouces offical Website with email and other
            facilities
          </p>
        </div>
      </div>
    </div>
  </Saos>
</section>

<!--cta  -->
<section>
  <div
    class=" container flex flex-col items-center px-6 py-20 space-y-12 justify-center mx-auto md:py-12 md:flex-col md:space-y-0 bg-gray-800 "
  >
    <h1
      class="text-5xl font-bold leading-tight text-center text-white md:text-4xl md:max-w-xl md:text-left"
    >
      Let's talk
    </h1>
    <p class=" text-center text-2xl w-2/3 ">
      Feel free to contact me via email at lennoxkamara@yahoo.com or contact
      +23276359164.
    </p>
  </div>
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
