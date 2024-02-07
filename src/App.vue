<script>
//facciamo l'import dei componenti 
import Header from "./components/Header.vue"

//poi l'export
export default {
    components: {
        Header,
    }
}
</script>

<template>
    <Header></Header>
</template>

<style lang="scss">
@use "./assets/styles/general.scss"
</style>
