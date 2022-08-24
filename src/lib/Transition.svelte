<script>
	import { fly } from 'svelte/transition';
	export let refresh = '';
</script>

{#key refresh}
	<div in:fly={{ y: -50, duration: 550, delay: 600 }} out:fly={{ y: -50, duration: 550 }}>
		<slot />
	</div>
{/key}
