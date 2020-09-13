<script>
	// import {Alert, Jumbotron} from 'sveltestrap'
	import Header from '../components/Header.svelte'
</script>

<template lang="pug">
	Header(title="accueil")
	.alert.alert-info
		h3 Bienvenue!
	.jumbotron
		h3.display-3  plein de services
		p.lead ici y'a de quoi faire!
</template>
