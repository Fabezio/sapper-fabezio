<script>
	export let segment;
	let navLinks = [
		{file: 'services', label: 'Services'},
		{file: 'skills', label: 'Compétences'},
	]
	
</script>

<nav class="bg-primary">
	<ul>
		<li><a class="text-light" aria-current="{segment === undefined ? 'page' : undefined}" href=".">Accueil</a></li>
		{#each navLinks as navLink}
			<li><a class="text-light" aria-current="{segment === navLink.file ? 'page' : undefined}" href="{navLink.file}">{navLink.label}</a></li>
		{/each}
  </ul>
</nav>	

<style lang="stylus">
nav
	border-bottom 1px solid rgba(255,62,0,0.1)
	font-weight 300
	padding 0 1em

ul
	margin 0
	padding 0
	&::after
		content ''
		display block
		clear both

li
	display block
	float left

[aria-current]
	position relative
	display inline-block

[aria-current]::after
	position absolute
	content ''
	width calc(100% - 1em)
	height 2px
	background-color rgb(255,62,0)
	display block
	bottom -1px

a
	text-decoration none
	padding 1em 0.5em
	display block
</style>

