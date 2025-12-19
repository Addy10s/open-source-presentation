<div class="flex h-screen bg-[url('/src/routes/Projects/slide6/background1.png')] bg-center">
	<div class="m-auto flex flex-col items-center">
		<h3 class="text-[10rem] font-black">Speaking of...</h3>
        <h3 class="text-[1.5rem] font-black">Github.com/Addy10s/open-source-presentation</h3>
	</div>
</div>


<script lang="ts">
function handleKeydown(event: { key: string; }) {
	if (event.key === 'Enter') {
		window.location.replace('https://github.com/addy10s/open-source-presentation')
	}
}
</script>
<svelte:window on:keydown={handleKeydown} />