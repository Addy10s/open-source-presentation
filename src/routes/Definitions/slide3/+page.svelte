<div class="flex h-screen bg-[url('/src/routes/Definitions/slide3/background.png')] bg-center">
	<div class="m-auto">
		<h3 class="text-[6rem] font-black">What About Free Software?</h3>
		<h3 class="text-[2rem] italic"> And that's Free as in Freedom🦅</h3>
	</div>
</div>



<script lang="ts">
import { goto } from '$app/navigation';
function handleKeydown(event: { key: string; }) {
	if (event.key === 'Enter') {
		goto('slide4/')
	}
}
</script>
<svelte:window on:keydown={handleKeydown} />