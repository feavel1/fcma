<script>
	export let dark;
</script>

<nav class="flex justify-center w-full mb-8">
	<a class="mx-5 hover:underline" href="/">主页</a>
	<a class="mx-5 hover:underline" href="about">关于</a>
	<a
		href="/"
		class="mx-5 hover:underline"
		on:click|preventDefault={() => {
			dark = !dark;
		}}
		>{dark ? '☼' : '☾'}
	</a>
</nav>
