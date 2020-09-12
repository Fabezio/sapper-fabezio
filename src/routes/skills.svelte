<script>
	// import {Alert, Button} from 'sveltestrap'
	import Header from '../components/Header.svelte'
</script>
<!-- 
<svelte:head>
	<title>Sapper project template</title>
</svelte:head> -->

<template lang="pug">
	Header(title="Compétences")
	//- Alert(color="primary")
		h3 y'a de quoi faire

	.jumbotron.bg-info.text-light
		h3.display-3 Ce que nous savons faire
		p.lead si vous avez des doutes, voici un apeçu de nos 
			i talents

	//- .btn.btn-block.btn-primary.font-weight-bold.display-4 commencer


</template>

<style lang="stylus">

</style>
