<script>
  import Counter from "./lib/Counter.svelte";

  let src = '/src/assets/picole.png';

</script>

<main>

  <h1>VOTAÇÃO</h1>

  <img src={src} alt="Picolé"/>

  <h2>Volta picolé da WEG?</h2>

  <div id="contadores">
    <Counter />
  </div>
    
</main>

<style>

  img {
    width: 30%;
  }
</style>