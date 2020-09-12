<script>
    // import {} from 'sveltestrap'
    export let title = "titre"
    let website = "fabezio.fr"
</script>
<template lang="pug">
    svelte:head
        title {website} | {title}
    .text-center.mt-5.mb-4
        h1.text-uppercase {website}
        h2.text-capitalize {title}
    //- hr
</template>