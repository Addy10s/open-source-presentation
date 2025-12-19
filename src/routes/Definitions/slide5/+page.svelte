<div class="flex h-screen bg-[url('/src/routes/Definitions/slide5/background.png')] bg-center">
    <div class="m-auto">
        <h3 class="text-[5rem] font-black">What's the difference?</h3>
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