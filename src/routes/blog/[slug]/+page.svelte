
<script lang="ts">
    export let data;
</script>

<div>
  {#each data.names as { name, id  } (id)}
    <div class = "font-semibold">{name}</div>
  {/each}
</div>