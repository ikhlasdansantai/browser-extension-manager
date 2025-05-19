<script lang="ts">
	import ExtensionCard from '$components/ExtensionCard.svelte';
</script>

<div class="mt-8 grid gap-4 sm:grid-cols-2 lg:grid-cols-3">
	{#each Array(4) as item}
		<!-- content here -->
		<ExtensionCard />
	{/each}
</div>
