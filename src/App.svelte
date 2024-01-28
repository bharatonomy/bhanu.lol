<script lang="ts">
  import svelteLogo from "./assets/svelte.svg";
  import viteLogo from "/vite.svg";
  import Counter from "./lib/Counter.svelte";
  let rum: any;
  let count = 69;
  function terma() {
    let herd: any = "Changed Changed";
    // count += 2;
    rum.innerHTML = herd;
  }
</script>

<main class="text-center">
  <h1 class="text-5xl">Bharat Mishra</h1>
  <div bind:this={rum}>hh</div>
  <Counter />
  <button on:click={terma}>Click</button>
  <h2>{count}</h2>
</main>
