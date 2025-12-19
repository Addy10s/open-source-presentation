<div class="flex h-screen bg-[url('/src/routes/Projects/slide5/background1.png')] bg-center">
	<div class="m-auto flex flex-col items-center">
		<h3 class="text-[10rem] font-black">Development</h3>
	</div>
</div>


<script lang="ts">
import { goto } from '$app/navigation';
function handleKeydown(event: { key: string; }) {
	if (event.key === 'Enter') {
		goto('slide6/')
	}
}
</script>
<svelte:window on:keydown={handleKeydown} />