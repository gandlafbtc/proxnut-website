<script lang="ts">
  import "./app.css";
  import Footer from "./lib/Footer.svelte";

  import Header from "./lib/Header.svelte";
</script>

<Header />
<div
  class="pt-20 w-full p-2 flex flex-col items-center justify-center gap-"
  style="  background-image: linear-gradient(to bottom, rgba(255,255,255, 0.5) 0 100%),  url('/ice.jpg'); background-size: cover; "
>
  <img src="/X-bg.svg" alt="" class="w-32" />
  <img src="/proxnut_black.svg" alt="" class="h-16" />
  <h1>Protect or monetize web resources with a Cashu ecash proxy.</h1>

  <div class="pt-20 pb-10">
    <p class="font-bold text-lg">How it works</p>
  </div>
  <div
    class="w-full grid grid-cols-1 lg:grid-cols-3 gap-3 items-center justify-center p-2"
  >
    <div class="w-full flex justify-center">
      <div
        class="w-80 h-80 gap-2 flex flex-col bg-secondary items-center justify-start p-2 rounded-lg shadow-lg backdrop-filter backdrop-blur-sm top-0 bg-opacity-30"
      >
      <p class="text-primary font-bold text-lg">1. Install proxy as request handler</p>
      <p class="text-primary">
        Put proxnut as an intermediate hop between clients and you API. 
      </p>
      <img src="/glassed.png" alt="" class="w-32">
    </div>
    </div>
    <div class="w-full flex justify-center">
      <div
        class="w-80 h-80 gap-2 flex flex-col bg-secondary items-center justify-start p-2 rounded-lg shadow-lg backdrop-filter backdrop-blur-sm top-0 bg-opacity-30"
      >
      <p class="text-primary font-bold text-lg">2. Link to API</p> 
      <p class="text-primary">
        Choose which endpoints should be proxied by proxnut. 
      </p>
      </div>
    </div>
    <div class="w-full flex justify-center">
      <div
      class="w-80 h-80 gap-2 flex flex-col bg-secondary items-center justify-start p-2 rounded-lg shadow-lg backdrop-filter backdrop-blur-sm top-0 bg-opacity-30"
    >
      <p class="text-primary font-bold text-lg">3. Configure route settings</p>
      <p class="text-primary">
        Specify how much access to each route should cost. 
      </p>
      </div>
    </div>
  </div>
</div>

<Footer />
