<script >
//facciamo l'export
export default {
    name: "Comic",

    props: {
        propsImg: String,
        propsTitle: String,
    }
};


</script>

<template>
    <div class="col-3">
        <figure>
            <img :src="propsImg" alt="">
        </figure>
        <h4>{{ propsTitle }}</h4>
    </div>
</template>

<style lang="scss" scoped>
.col-3 {
    width: calc((100% /6) - (30px));
    height: 150px;
    display: flex;
    flex-direction: column;
    gap: 10px;

    margin-block: 30px;

    figure {
        width: 100%;
        height: 100%;

        img {
            width: 100%;
            height: 100%;

        }
    }

    h4 {
        color: white;
        font-size: 12px;
    }
}
</style>
