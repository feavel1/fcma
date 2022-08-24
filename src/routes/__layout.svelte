<script context="module">
	export const load = async ({ url }) => ({
		props: {
			key: url
		}
	});
</script>

<script>
	import '../app.css';
	import Nav from '$lib/Nav.svelte';
	import Transition from '$lib/Transition.svelte';
	import Footer from '../lib/Footer.svelte';
	export let key;
</script>

<Nav />
<Transition refresh={key}>
	<slot class="max-w-6xl mx-auto" />
	<Footer />
</Transition>
