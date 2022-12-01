<script lang="ts">
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <img src="https://w7.pngwing.com/pngs/943/692/png-transparent-butterfly-flying-butterflies-animals-brush-footed-butterfly-orange.png" class="logo" alt="butterfly" />
  </div>
  <h1>Kanimod</h1>

  <div class="card">
    <p>my current js abilities:</p>
    <Counter />
  </div>

  <p>
    HelLo i am under the button
  </p>

</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
</style>