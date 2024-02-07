<script>
//facciamo l'import dei componenti 
import Header from "./components/Header.vue"
import ComicsContainer from "./components/ComicsContainer.vue"
import IconsContainer from "./components/IconsContainer.vue"



//poi l'export
export default {
    components: {
        Header,
        ComicsContainer,
        IconsContainer,
    }
}
</script>

<template>
    <Header></Header>

    <main>
        <div id="black-container">
            <ComicsContainer></ComicsContainer>
        </div>

        <div id="blue-container">

            <IconsContainer></IconsContainer>
        </div>
    </main>
</template>

<style lang="scss">
@use "./assets/styles/general.scss"
</style>
