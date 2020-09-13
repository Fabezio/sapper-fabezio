<script>
	import Header from '../components/Header.svelte'
	let showGrid = false
	
</script>
	
<template lang="pug">
	Header(title="services")
	
	p Un panel de services est à votre disposition afin de déterminer au mieux vos besoins
	p Cliquez sur le bouton ci-dessous pour commencer
	
	//- button.btn.btn-block.btn-primary.font-weight-bold(onclick={ () => showGrid = !showGrid}) voir

</template>