<script>
	import '../app.css';
	import Footer from '../lib/Footer.svelte';
	import Nav from '../lib/Nav.svelte';
	let dark = true;
</script>

<div class:dark>
	<main class="bg-zinc-300 dark:bg-zinc-800 dark:text-white p-8 min-h-screen">
		<Nav bind:dark />
		<slot class="max-w-6xl mx-auto" />
	</main>
	<Footer />
</div>
