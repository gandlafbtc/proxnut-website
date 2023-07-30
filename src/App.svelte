<script lang="ts">
  import "./app.css";
  import Footer from "./lib/Footer.svelte";

  import Header from "./lib/Header.svelte";
    import HowItWorks from "./lib/HowItWorks.svelte";
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
  <HowItWorks></HowItWorks>

</div>
<div class="flex py-20 flex-col gap-10 bg-gradient-to-b from-secondary to-white">
  <p class="text-center font-bold text-lg">How to Install</p>
  <p class="text-center">
    Proxnut is open source. To leverage proxnut for your own infrastructure follow these steps.
  </p>
<div>
coming soon
</div>
</div>

<Footer />
