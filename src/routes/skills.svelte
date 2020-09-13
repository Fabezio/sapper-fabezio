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

	.jumbotron.bg-info.text-light
		h3.display-3 Ce que nous savons faire
		p.lead si vous avez des doutes, voici un aperçu de nos 
			i créations

</template>
