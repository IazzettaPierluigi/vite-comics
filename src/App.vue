<script>
//facciamo l'import dei componenti 
import Header from "./components/Header.vue"
import ComicsContainer from "./components/ComicsContainer.vue"


//poi l'export
export default {
    components: {
        Header,
        ComicsContainer,
    }
}
</script>

<template>
    <Header></Header>

    <main>
        <ComicsContainer></ComicsContainer>
    </main>
</template>

<style lang="scss">
@use "./assets/styles/general.scss"
</style>
