<script >
//facciamo l'export
export default {
    name: "Comic",

    props: {
        propsImg: String,
    }
};


</script>

<template>
    <div class="col-3">
        <figure>
            <img :src="propsImg" alt="">
        </figure>
        <h4></h4>
    </div>
</template>

<style lang="scss" scoped>
.col-3 {
    width: calc(100% /6);
    height: 200px;

    figure {
        width: 100%;
        height: 100%;

        img {
            width: 100%;
            height: 100%;
        }
    }

    h4 {}
}
</style>
