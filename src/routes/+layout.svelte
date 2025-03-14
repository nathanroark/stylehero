<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<svelte:head>
	<meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1" />
	<title>App</title>
</svelte:head>

<main class="dark">
	<div class="bg-background text-foreground min-h-screen flex-1">
		{@render children()}
	</div>
</main>
