<script>
  import Counter from "$lib/Counter.svelte";
</script>

<svelte:head>
  <title>Svelte Template</title>
</svelte:head>

<img src="../static/image/logo2.png">

<main>
  <h1 class="text-primary">Hello world!</h1>
  <a href="/home">HOME</a>
  <a href="/login">LOGIN</a>
  <a href="/signup">SIGNUp</a>
  <a href="/home">HOME</a>


</main>

<style lang="scss">
  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  h1 {
    text-transform: uppercase;
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 4rem auto;
    max-width: 14rem;
  }

  p {
    max-width: 14rem;
    margin: 2rem auto;
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
