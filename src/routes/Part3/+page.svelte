<script>
	import TopNavInside from '$lib/component/topnav/TopNavInside.svelte';
	import { fade } from 'svelte/transition';
</script>

<div class="p-2">
	<TopNavInside></TopNavInside>
	<div class="container flex items-center justify-center w-full h-full mx-auto" in:fade>
		<div class="w-full space-y-5">
			<h1 class="text-center h1">Part 3</h1>
			<div class="w-full h-full p-2 bg-red-400 rounded-xl">Downloadable Content</div>
		</div>
	</div>
</div>
