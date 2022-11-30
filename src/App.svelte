<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <img src="https://testoria.pl/wp-content/uploads/2021/02/https-_hypebeast.com_image_2021_02_chris-torres-nyan-cat-foundation-10-year-anniversay-auction-001.jpg" class="logo" alt="nyancat" />
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