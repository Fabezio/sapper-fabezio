<script>
	// import {Alert, Button} from 'sveltestrap'
	import {env} from 'svelte'
	import Header from '../components/Header.svelte'
	let myenv = processenv
</script>
<!-- 
<svelte:head>
	<title>Sapper project template</title>
</svelte:head> -->

<template lang="pug">
	Header(title="variable d'environnement")
	//- Alert(color="primary")
		h3 y'a de quoi faire
	#if myenv
		code.jumbotron
			pre {myenv}
	#else 
		.alert.alert-danger pas d'environnemennt configuré ici

	//- .btn.btn-block.btn-primary.font-weight-bold.display-4 commencer


</template>

<style lang="stylus">

</style>
