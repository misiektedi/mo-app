<script>
	import '../assets/css/fonts.css';
	import '../assets/css/main.css';
</script>

<svelte:head>
	<title>MO App</title>
</svelte:head>

<header class="mo-header">
	<a href="/"><h1>MO App</h1></a>
	<a href="/produkty">Produkty</a>
	<a href="/kontakt">Kontakt</a>
</header>

<main>
	<slot />
</main>

<footer class="mo-footer">
	<p>Copyright 2024 - @misiektedi</p>
</footer>