<script lang="ts">
	import '../app.css';

	let { children } = $props();
	import Navbar from '$components/Navbar.svelte';
</script>

<Navbar />

<main class="mt-20">
	{@render children()}
</main>
