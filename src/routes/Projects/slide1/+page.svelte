<div class="flex h-screen bg-[url('/src/routes/background.png')] bg-center">
	<div class="m-auto flex flex-col items-center">
		<h3 class="text-[5rem] font-black">Do I use any Open Source Software?</h3>
	</div>
</div>



<script lang="ts">
import { goto } from '$app/navigation';
function handleKeydown(event: { key: string; }) {
	if (event.key === 'Enter') {
		goto('slide2/')
	}
}
</script>
<svelte:window on:keydown={handleKeydown} />