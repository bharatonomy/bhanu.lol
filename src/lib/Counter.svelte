<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button class="bg-pink-500 p-2 rounded-lg" on:click={increment}>
  count is {count}
</button>
