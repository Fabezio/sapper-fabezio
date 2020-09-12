<script>
	import Nav from '../components/Nav.svelte';
	import DownloadTape from '../components/DownloadTape.svelte';
	// import {Container} from 'sveltestrap';

	export let segment;
</script>


<template lang="pug" >
	Nav({segment})
	//- main
	DownloadTape
	.container
		slot
</template>
<!-- <Nav {segment}/>
<main>
	<slot></slot>
	
</main> -->
<style>
	main {
		position: relative;
		/* max-width: 56em; */
		background-color: skyblue;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>
