<script lang="ts">
	let count = 0;
	function inc() {
		count += 1;
	}
</script>

<h1>you clicked the button {count} times</h1>

{#if count > 5}
	<h1>you clicked the button more than 5 times</h1>
{/if}
<button on:click={inc}>click</button>
