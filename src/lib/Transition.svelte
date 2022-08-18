<script>
	import { fly, fade } from 'svelte/transition';
	export let url;
</script>

{#key url}
	<div in:fly={{ y: 100, duration: 1500 }}>
		<slot />
	</div>
{/key}
