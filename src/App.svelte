<script>
  let count = 0;

  function increment() {
    count++;
  }
</script>

<main>
  <h1>Number {count}</h1>
  <p>This is a simple Svelte app.</p>
  <button on:click={increment}>+1</button>
</main>

<style>
</style>
