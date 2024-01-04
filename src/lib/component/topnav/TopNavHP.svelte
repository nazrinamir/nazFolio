<script lang="ts">
	import { goto } from '$app/navigation';
	import { Drawer, getDrawerStore } from '@skeletonlabs/skeleton';
	import type { DrawerSettings, DrawerStore } from '@skeletonlabs/skeleton';
	import { initializeStores } from '@skeletonlabs/skeleton';
	import { draw } from 'svelte/transition';
	import DrawerHome from '../drawer/drawerHome.svelte';

	initializeStores();
	const drawerStore = getDrawerStore();
</script>

<div class="flex justify-between w-full">
	<button
		class="rounded-xl playbutton btn"
		on:click={() => {
			drawerStore.open();
		}}
	>
		more
	</button>
	<button class="rounded-xl playbutton btn"> Language </button>
</div>
<Drawer>
	<DrawerHome></DrawerHome>
</Drawer>

<style>
	.playbutton {
		background-image: linear-gradient(to bottom, #467ac8, #00c2d9);
		border: 1px solid #467ac8;
		box-shadow:
			inset 0px 2px 0px 0px #00c2d9,
			inset 0px -3px 0px 0px #467ac8;
	}
</style>
