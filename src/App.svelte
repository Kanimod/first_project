<script lang="ts">
  import Counter from './lib/Counter.svelte'
  import Image from './public/pngwing.com.png'
</script>

<main>
  <div>
    <Image src="./public/pngwing.com.png"  class="logo" alt="butterfly" />
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