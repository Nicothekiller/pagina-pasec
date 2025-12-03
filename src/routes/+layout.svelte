<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import Taskbar from '$lib/components/Taskbar.svelte';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<Taskbar />
{@render children()}
