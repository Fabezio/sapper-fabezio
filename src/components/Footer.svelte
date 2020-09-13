<script>
  import Chips from './Chips.svelte'
</script>

<template lang="pug" >
.inline-block.alert.alert-secondary.w-100.text-center
  span.mr-3
    | fabezio.fr 
    | &copy; 
    | {new Date().getFullYear()}
    
  a(href="https://github.com/Fabezio/sapper-fabezio" target="_blank") 
    Chips(icon="fab fa-github-alt" )
      span mon code source
    
</template>