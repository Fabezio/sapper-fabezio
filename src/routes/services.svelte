<script>
	// import {Alert, Button} from 'sveltestrap'
	import Header from '../components/Header.svelte'
</script>
<!-- 
<svelte:head>
	<title>Sapper project template</title>
</svelte:head> -->

<template lang="pug">
	Header(title="services")
	//- Alert(color="primary")
		h3 y'a de quoi faire

	p Un panel de services est à votre disposition afin de déterminer au mieux vos besoins
	p Cliquez sur le bouton ci-dessous pour commencer

	.btn.btn-block.btn-primary.font-weight-bold commencer


</template>

<style lang="stylus">

</style>
