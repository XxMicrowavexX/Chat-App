<script>
  import { goto } from "$app/navigation";

  // ...
  function gto() {
    goto("/signup", {});
  }
</script>

<div class="h-96 flex items-center justify-center bg-gray-900">
  <div class="border-orange-500 border-8 rounded-3xl">
    <div class="pl-20 pr-20 pb-10 pt-10">
      <p
        class="pb-2 text-7xl text-white font-semibold"
        style="font-family: 'DM Sans', sans-serif;"
      >
        Welcome to insert name
      </p>
      <p class="text-white text-center">
        insert name Messeger is the fastest most reliable messaging service ever to
        be made.
      </p>
    </div>
  </div>
</div>
<div class="flex flex-col items-center">
  <button
    on:click={gto}
    class="transition ease-in-out self-center flex mx-1/2 text-white focus:ring-4 border-orange-500 border-4 rounded-lg text-lg px-5 py-2.5 mr-2 mb-2 bg-gray-900 hover:bg-orange-500 focus:outline-none focus:ring-gray-800"
    style="font-family: 'DM Sans', sans-serif;"
  >
    Get Started
  </button>
</div>
