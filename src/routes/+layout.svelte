<script>
	import Header from './Header.svelte';
	import Sidebar from './Sidebar.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header />
	<Sidebar />

	<main>
		<slot />
	</main>
</div>

<style>
	.app {
	}
</style>
