<script>
	import Classes from '../lib/Classes.svelte';
	import Questions from '../lib/Questions.svelte';
</script>

<div class="max-w-xl mx-auto">
	<h1 class="font-bold text-3xl my-5">
		关于深信影视文化传媒协会<c class="text-cyan-400">F</c>CMA
	</h1>

	<p class=" my-5 flex flex-wrap justify-start text-purple-500">✦ 影视 摄影 哲学 音乐 ✦</p>
	<h2 class="font-bold text-2xl my-5">协会主要课程:</h2>

	<hr class="my-4" />

	<Classes />

	<h2 class="font-bold text-2xl my-5">↓Q&A 基本问题解答↓</h2>
	<hr class="my-4" />
	<div>
		<Questions title="这个社团是做什么的?"
			>我们是深信影视与文化传媒协会，社团主要给想在正确的时间认识正确的人汇合的地方。我们有讨论电影，哲学，编剧，摄影，美食还有很多。要是自己和艺术沾边都可以进来一起讨论，分享知识，认识共同爱好的人。
		</Questions>
		<Questions title="社团有哪些活动？">
			我们主要有<a href="/" class="hover:underline text-blue-400">“电影文化分析与制作”</a
			>、“哲学理论”、<a href="/" class="hover:underline text-blue-400">“摄影”</a
			>、“时尚摄影”、“故事王”等活动，官网可以找到活动详细信息。
		</Questions>
		<Questions title="我们社团有哪些人?"
			>进社团的人大部分都是对摄影，电影，艺术，哲学，政治，美学，音乐，绘画等内容感兴趣的人。
		</Questions>
		<Questions title="社团有社费吗？">- 有。 社团费用最低50RMB，最高100RMB</Questions>
		<Questions title="社费包括哪些东西？"
			><ol class="list-decimal list-inside">
				<li>（可选）社团梯子🪜（为了阅读墙外摄影资料）</li>
				<li>（可选）社团荣誉书籍📖</li>
				<li>漂流箱子📦</li>
				<li>（可选）稀有图册和阅读资料📚</li>
				<li>投影仪📽</li>
			</ol>
		</Questions>
		<Questions title="我决定加入社团，我在哪报名？">
			你可以在我们的摊位，扫码加微信群并留意<c class="text-green-400">公众号</c>或<c
				class="text-green-400">微信群</c
			>公告的面试通知。 要是没有扫描到可以在下面查看报名方式。
		</Questions>
	</div>
	<hr class="my-4" />

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
</div>
