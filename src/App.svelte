<script>
	export let name;

	import MenuApp from './menu/App.svelte';
	import HeaderApp from './header/App.svelte';
	import FooterApp from './footer/App.svelte';

	console.log('this is src/App.svelte');
</script>

<main>
	<div>hello {name}, nothing to see here. look at JS console</div>

	<MenuApp/>
	<HeaderApp/>
	<FooterApp/>
</main>

<style>
	main { font-family: monospace; }
</style>
