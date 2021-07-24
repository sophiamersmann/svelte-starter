<script>
  import Counter from './lib/Counter.svelte';
</script>

<main>
  <h1>Hello world!</h1>
  <Counter />
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    margin: 0 auto;
    padding: 1em;
    text-align: center;
  }

  h1 {
    max-width: 14rem;
    margin: 2rem auto;
    color: #ff3e00;
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    text-transform: uppercase;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }
  }
</style>
