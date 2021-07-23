<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button on:click={increment}>
  Clicks: {count}
</button>

<style>
  button {
    width: 200px;
    padding: 1em 2em;
    border: 2px solid rgba(255, 62, 0, 0);
    border-radius: 2em;
    outline: none;
    background-color: rgba(255, 62, 0, 0.1);
    color: #ff3e00;
    font-family: inherit;
    font-size: inherit;
    cursor: pointer;
    font-variant-numeric: tabular-nums;
  }

  button:focus {
    border: 2px solid #ff3e00;
  }

  button:active {
    background-color: rgba(255, 62, 0, 0.2);
  }
</style>
