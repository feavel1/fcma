<script>
	import { onMount } from 'svelte';

	export let segment;
	let darkS;

	onMount(() => {
		if (
			localStorage.theme === 'dark' ||
			(!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)
		) {
			document.documentElement.classList.add('dark');
		} else {
			document.documentElement.classList.remove('dark');
		}
	});

	function toggleDarkMode() {
		if (document.documentElement.classList.toggle('dark')) {
			localStorage.setItem('theme', 'dark');
			darkS = false;
		} else {
			localStorage.removeItem('theme');
			darkS = true;
		}
	}
</script>

<nav class="flex justify-center w-full mb-8">
	<a class="mx-5 hover:underline {segment === '/' ? 'current' : ''}" href="/">主页</a>
	<a class="mx-5 hover:underline {segment === '/about' ? 'current' : ''}" href="about">关于</a>
	<!-- <a
		href="/"
		class="mx-5 hover:underline"
		on:click|preventDefault={() => {
			dark = !dark;
		}}
		>{dark ? '☼' : '☾'}
	</a> -->
	<c on:click={toggleDarkMode} class="mx-5 hover:underline">{darkS ? '☼' : '☾'}</c>
</nav>
