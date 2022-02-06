<script>
	import Title from '$lib/components/title.svelte';
	import '../app.css';
</script>

<header>
	<Title title="Ninja Gaming Guides" />
</header>

<main>
	<!-- page content -->
	<slot />
</main>

<footer>
	<p>Copyright 2022 Ninja Gaming Guides</p>
</footer>

<style>
	header {
		display: flex;
		justify-content: center;
		align-items: center;
	}

	main {
		max-width: 960px;
		margin: 20px auto;
	}

	footer {
		text-align: center;
	}
</style>
