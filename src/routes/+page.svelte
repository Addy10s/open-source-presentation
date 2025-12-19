<div class="flex h-screen bg-[url('/src/routes/background.png')] bg-center">
	<div class="m-auto">
		<h3 class="text-[10rem] font-black">Open Source!</h3>
	</div>
</div>


<script lang="ts">
import { goto } from '$app/navigation';
function handleKeydown(event: { key: string; }) {
	if (event.key === 'Enter') {
		goto('Definitions/slide1/')
	}
}
</script>
<svelte:window on:keydown={handleKeydown} />