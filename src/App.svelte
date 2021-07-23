<script>
  import logo from "./assets/svelte.png";
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <img src={logo} alt="Svelte Logo" />
  <h1>Hello world!</h1>

  <Counter />

  <p>
    Visit <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte
    apps.
  </p>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
    the officially supported framework, also powered by Vite!
  </p>
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
      Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  main {
    margin: 0 auto;
    padding: 1em;
    text-align: center;
  }

  img {
    width: 16rem;
    height: 16rem;
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

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }

    p {
      max-width: none;
    }
  }
</style>
