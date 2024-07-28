<script lang="ts">
	import '../styles/app.css'

	let { children } = $props()
</script>

<svelte:head>
	<title>Design thinking</title>
</svelte:head>

{@render children()}