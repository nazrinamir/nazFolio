<script>
	import TopNavInside from '$lib/component/topnav/TopNavInside.svelte';
	import { fade } from 'svelte/transition';
</script>

<div class="p-2">
	<TopNavInside></TopNavInside>
	<div class="container flex items-center justify-center h-full mx-auto" in:fade>
		<div class="w-full space-y-5">
			<h1 class="text-center h1">Part 2</h1>
			<div class="p-2 space-y-2 bg-red-400 rounded-xl">
				<div class="flex w-full gap-2">
					<div class="w-1/2 p-2 bg-blue-400 rounded-xl">data Visualization 1</div>
					<div class="w-1/2 p-2 bg-blue-400 rounded-xl">data Visualization 2</div>
				</div>
				<div class="p-2 bg-green-400 rounded-xl">data Visualization 3</div>
				<div class="p-2 bg-yellow-400 rounded-xl">data Visualization 4</div>
			</div>
		</div>
	</div>
</div>
