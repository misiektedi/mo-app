<script>
	import '../assets/css/fonts.css';
</script>

<svelte:head>
	<title>MO App</title>
</svelte:head>

<header>
	<a href="/"><h1>MO App</h1></a>
	<a href="/kontakt">Kontakt</a>
</header>

<main>
	<slot />
</main>

<footer>
	<p>2024</p>
</footer>