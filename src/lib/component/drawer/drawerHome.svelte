<script>
	import { goto } from '$app/navigation';
</script>

<div class="flex h-full">
	<div class="p-2 border-r-2 border-slate-600 sp1ace-y-5">
		<div class="w-full">
			<button
				class="border-b border-slate-600 btn"
				on:click={() => {
					goto(`/AboutMe`);
				}}>About Me</button
			>
		</div>
		<div class="w-full">
			<button
				class="border-b border-slate-600 btn"
				on:click={() => {
					goto(`/Part1`);
				}}>Part 1</button
			>
		</div>
		<div class="w-full">
			<button
				class="border-b border-slate-600 btn"
				on:click={() => {
					goto(`/Part2`);
				}}>Part 2</button
			>
		</div>
		<div class="w-full">
			<button
				class="border-b border-slate-600 btn"
				on:click={() => {
					goto(`/Part3`);
				}}>Part 3</button
			>
		</div>
	</div>
	<div class="w-full p-4">part drawer details</div>
</div>

<style>
	.playbutton {
		background-image: linear-gradient(to bottom, #467ac8, #00c2d9);
		border: 1px solid #467ac8;
		box-shadow:
			inset 0px 2px 0px 0px #00c2d9,
			inset 0px -3px 0px 0px #467ac8;
	}
</style>
