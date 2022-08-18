<script>
	import '../app.css';
	import { page } from '$app/stores';
	import Nav from '$lib/Nav.svelte';
	import Transition from '$lib/Transition.svelte';
	import Footer from '../lib/Footer.svelte';
	let dark = true;
</script>

<div class:dark>
	<main class="bg-zinc-300 dark:bg-zinc-800 dark:text-white p-8 min-h-screen">
		<Nav bind:dark />
		<Transition url={$page.url}>
			<slot class="max-w-6xl mx-auto" />
			<Footer />
		</Transition>
	</main>
</div>
