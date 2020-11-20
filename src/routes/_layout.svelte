<script>
	import Nav from '../components/Nav.svelte';
</script>

<style type='text/scss'>
@import "../styles/theme.scss";

	main {
		position: relative;
		max-width: $site-width;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>

<Nav />

<main >
	<slot></slot>
</main>