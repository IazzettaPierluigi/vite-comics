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

<style lang="scss" scoped>
header {
    //style di header
    width: 60%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 20px;
    height: 104px;



    //style del figure
    figure {
        width: 80px;
        height: 80px;
        margin-bottom: 20px;

        //style del img
        img {
            width: 100%;
            height: 100%;
        }
    }

    .lista {
        //style del div con classe lista

        ul {
            //style della UL
            display: flex;
            flex-direction: row;
            gap: 10px;
            text-transform: uppercase;

            li {
                list-style-type: none;
                line-height: 100px;
                font-weight: bold;

            }

            li:hover {

                border-bottom: 4px solid #0282f9;
            }

        }
    }
}
</style>
