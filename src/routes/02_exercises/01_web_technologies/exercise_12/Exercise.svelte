<script>
	let clicked = false;
</script>

<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		click here
	</button>
	<!--  -->
	{#if clicked}
	<p> You have clicked the button</p>
	{:else}
	<p>You have not clicked the button</p>
	{/if}
</div>
