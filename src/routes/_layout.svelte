<script>
	import Nav from '../components/Nav.svelte';
	// import DownloadTape from '../components/DownloadTape.svelte';
	import Footer from '../components/Footer.svelte';
	
	export let segment;
	
</script>

<template lang="pug" >

	Nav({segment})

	.container
		slot
		
	Footer
			
</template>
