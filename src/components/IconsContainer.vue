<script >
//facciamo l'export
export default {
    name: "IconsContainer",
    data() {
        return {
            listItems: [
                {
                    text: "digital comics",
                    img: "buy-comics-digital-comics.png"
                },

                {
                    text: "dc merchandise",
                    img: "buy-comics-merchandise.png"
                },

                {
                    text: "subscription",
                    img: "buy-comics-shop-locator.png"
                },

                {
                    text: "comic shop locator",
                    img: "buy-comics-subscriptions.png"
                },

                {
                    text: "dc power visa",
                    img: "buy-dc-power-visa.svg"
                },


            ]
        }
    }
};


</script>

<template>
    <div class="container">
        <ul>
            <li v-for="(element, index) in  listItems " :key="index">
                <div id="text-ico">
                    <img :src="`../src/assets/img/${element.img}`" alt="">
                    <p>{{ element.text }}</p>
                </div>
            </li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
.container {
    width: 60%;
    margin: auto;
    padding-block: 50px;

    ul {
        display: flex;
        justify-content: space-around;

        li {
            list-style: none;
            text-transform: uppercase;
            color: white;


            #text-ico {
                display: flex;
                align-items: center;
                gap: 5px;

                img {
                    width: 50px;
                    height: 50px;
                }
            }
        }
    }
}
</style>
