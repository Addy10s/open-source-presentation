<div class="flex h-screen bg-[url('/src/routes/Definitions/slide6/background.png')] bg-center">
    <div class="m-auto">
        <h3 class="text-[5rem] font-bold">✨Benefits of OSS✨</h3>
    </div>
</div>



<script lang="ts">
import { goto } from '$app/navigation';
function handleKeydown(event: { key: string; }) {
	if (event.key === 'Enter') {
		goto('/Licenses/slide1/')
	}
}
</script>
<svelte:window on:keydown={handleKeydown} />