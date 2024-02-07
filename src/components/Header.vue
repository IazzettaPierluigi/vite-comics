<script >
//facciamo l'export
export default {
    name: "Header",
};
</script>

<template>
    <header>

        <figure>
            <img src="../assets/img/dc-logo.png" alt="">
        </figure>
        <div class="lista">
            <ul>
                <li>characters</li>
                <li>comics</li>
                <li>movies</li>
                <li>tv</li>
                <li>games</li>
                <li>collectibles</li>
                <li>videos</li>
                <li>fans</li>
                <li>news</li>
                <li>shop</li>
            </ul>
        </div>
    </header>
</template>

<style lang="scss">
header {
    //style di header
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;

    figure {
        width: 100px;
        background-color: red;

        img {
            width: 100%;
        }
    }

    .lista {
        //style del div con classe lista

        ul {
            //style della UL
            display: flex;
            flex-direction: row;

            li {
                list-style-type: none;
            }
        }
    }
}
</style>
