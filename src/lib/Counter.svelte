<script lang="ts">
  let count: number = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment}>
  {#if count}
    {#if count==1}
       {count} available milf  
    {:else}
       {count} available milfs
    {/if}
  {:else}
    click for milfs
  {/if}
</button>
