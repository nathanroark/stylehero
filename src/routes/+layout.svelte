<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<svelte:head>
	<meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1" />
	<title>StyleHero</title>
</svelte:head>

<main class="dark">
	<div class="bg-background text-foreground min-h-screen">
		{@render children()}
	</div>
</main>
