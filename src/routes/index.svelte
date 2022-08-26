<script>
	import Wave01 from '$lib/Wave01.svelte';
	import Circles from '../lib/Circles.svelte';
	import Classes from '../lib/Classes.svelte';
	import Lines from '../lib/Lines.svelte';
	import Wave02 from '../lib/Wave02.svelte';
</script>

<title>FCMA - Home</title>

<div class="max-w-xl mx-auto">
	<div class="min-h-screen">
		<h1 class="font-bold text-3xl my-5">
			欢迎你来到<c class="text-cyan-400">F</c>CMA官网
		</h1>
		<p>
			可以在我们的原版的 <a
				href="https://www.notion.so/fcma/c8a36861b7a24d1191b578bf7d18c079"
				target="_blank"
				class="text-2xl font-bold hover:underline">notion网站</a
			> 阅读更多资料
		</p>

		<div class="flex justify-between py-8">
			<h1 class="text-3xl "><c class="text-cyan-400">F</c>CMA</h1>
			<Lines />
		</div>

		<hr class="mb-8" />

		<Circles />

		<hr class="my-8" />

		<div class="flex justify-between my-8">
			<Lines />
			<h1 class="text-3xl "><a href="/" class="text-cyan-400">F</a>CMA</h1>
		</div>
	</div>

	<div class="flex flex-wrap justify-center text-gray-800 dark:bg-cyan-400 rounded">
		<div class="w-full md:w-1/2 lg:w-1/3 p-8">
			<div class="p-8">
				<h1 class="text-3xl font-bold">...</h1>
				<p>
					前往 <a
						href="https://www.notion.so/fcma/c8a36861b7a24d1191b578bf7d18c079"
						target="_blank"
						class="text-3xl font-bold hover:underline">作品</a
					> 阅读更多资料
				</p>
			</div>
		</div>
		<div class="w-full md:w-1/2 lg:w-1/3 p-8">
			<div class="p-8">
				<h1 class="text-3xl font-bold">///</h1>
				<p>
					想理解更多请前往
					<a
						href="https://www.notion.so/fcma/c8a36861b7a24d1191b578bf7d18c079"
						target="_blank"
						class="text-3xl font-bold hover:underline">notion网站</a
					>
					阅读哦
				</p>
			</div>
		</div>
	</div>

	<hr class="my-8" />

	<div class="my-10">
		<div class="bg-indigo-300 flex justify-center items-center p-10 rounded-t-xl ">
			<h1 class="bold text-xl">🎉 欢迎新生加入 🎉</h1>
		</div>
		<Wave01 />
		<div class="flex justify-center py-10 items-center text-3xl dark:text-cyan-400 ">
			影视与文化传媒协会
		</div>
		<Wave02 />
		<div class="flex justify-center items-center bg-blue-300 p-10 rounded-b-xl">🎬 📸 🎶 💭</div>
	</div>

	<div>协会主要课程:</div>

	<hr class="my-8" />

	<Classes />
</div>
