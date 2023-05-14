<script>
  export let counter;

  function increment() {
    counter ++;
  }
</script>

<button on:click={increment}>
  Counter: {counter}
</button>