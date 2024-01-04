<script lang="ts">
	import { goto } from '$app/navigation';
	import TopNavHp from '$lib/component/topnav/TopNavHP.svelte';
	import { fade } from 'svelte/transition';
</script>

<div class="p-2">
	<TopNavHp></TopNavHp>
	<div class="container flex items-center justify-center h-full mx-auto" in:fade>
		<div class="w-full h-full space-y-5">
			<h1 class="text-center h1">Welcome</h1>
		</div>
	</div>
</div>
