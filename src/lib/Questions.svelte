<script>
	export let title;
</script>

<div class="flex flex-col my-2">
	<div class="max-w-fit px-2 text-red-500 bg-zinc-900 rounded-md text-sm">
		{title}
	</div>
	<div class="indent-8 text-gray-400">
		<slot />
	</div>
</div>
