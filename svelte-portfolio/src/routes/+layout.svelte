<script>
	import favicon from '$lib/assets/cat.svg';
	import '../app.css';
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>Floya-self</title>
</svelte:head>

<slot />