<script >
//facciamo l'export
export default {
    name: "IconsContainer",
    data() {
        return {
            listItems: [
                {
                    text: "digital comics",
                    img: "../assets/img/buy-comics-digital-comics.png"
                },

                {
                    text: "dc merchandise",
                    img: "../assets/img/buy-comics-merchandise.png"
                },

                {
                    text: "subscription",
                    img: "../assets/img/buy-comics-digital-comics.png"
                },

                {
                    text: "comic shop locator",
                    img: "../assets/img/buy-comics-digital-comics.png"
                },

                {
                    text: "dc power visa",
                    img: "../assets/img/buy-comics-digital-comics.png"
                },


            ]
        }
    }
};


</script>

<template>
    <div class="container">
        <ul>
            <li v-for="(element, index) in listItems" :key="index">
                <div id="text-ico">
                    <img :src="element.img" alt="">
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

                img {
                    width: 50px;
                    height: 20px;
                }
            }
        }
    }
}
</style>
