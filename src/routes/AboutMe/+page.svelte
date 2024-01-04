<script lang="ts">
	import { goto } from '$app/navigation';
	import TopNavHp from '$lib/component/topnav/TopNavHP.svelte';
	import { fade } from 'svelte/transition';
</script>

<div class="p-2">
	<TopNavHp></TopNavHp>
	<div class="container flex items-center justify-center h-full mx-auto" in:fade>
		<div class="w-full h-full space-y-5">
			<h1 class="text-center h1">Hi (Name)</h1>

			<div class="flex w-full h-full space-x-5">
				<div class="w-1/2 p-2 bg-red-400 rounded-xl h-fix">
					<div class="flex items-center justify-center">
					<div>
						(Image)
					</div>
					</div>
					<div>name</div>
				</div>
				<div class="w-1/2 p-2 bg-green-400 rounded-xl h-fix">
					<div>about Me</div>
					<div>Objective</div>
					<div>Objective</div>
				</div>
			</div>
			<div class="p-2 bg-blue-400 rounded-xl">
				<div>
					school
				</div>
				<div>
					school
				</div>
				<div>
					school
				</div>
				<div>
					school
				</div>
				<div>
					school
				</div>
				<div>
					school
				</div>
			</div>
			<div class="w-full p-2 bg-yellow-400 rounded-xl">
				<div>
					skills
				</div>
			</div>
		</div>
	</div>
</div>
