<script>
	import Header from '$lib/header.svelte';
</script>

<Header />
<main>
	<slot />
</main>

<footer>Copywrite Now</footer>

<!-- <style>
	:global(header) {
		background: red;
		nav {
			background: blue;
		}
	}
</style> -->
