<script>
  let current = "";
</script>
<p class:myClassName={current} style="color:red" />

<!-- We will cover buttons later on! -->
<button class="btn btn-secondary" on:click={() => (current = "messi")}>
  Messi
</button>

<button class="btn btn-secondary" on:click={() => (current = "ronaldo")}>
  Ronaldo
</button>

<button class="btn btn-secondary" on:click={() => (current = "neymar")}>
  Neymar
</button>
