<script>
	import { page } from "$app/stores";
	import * as Collection from "$lib/index.js";
</script>

{#if Collection[$page.params.id]}
	<svelte:component this={Collection[$page.params.id]} />
{:else}
	<h1>404</h1>
{/if}
