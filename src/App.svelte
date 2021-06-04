<script>
	import Navbar from "./lib/Navbar.svelte";
</script>


<main>
	<Navbar/>	

</main>

<style>
	main {
		padding: 1em;
		max-width: 1920px;
		margin: 0 auto;
	}

	

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>