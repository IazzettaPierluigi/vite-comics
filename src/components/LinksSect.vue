<script >
//facciamo l'export
export default {
    name: "LinkSect",

};


</script>

<template>
    <div id="link-container">
        <div id="sect-container">
            <div id="cols-container">
                <div id="col">
                    <h4>dc comics</h4>
                    <ul>
                        <li>characters</li>
                        <li>comics</li>
                        <li>movies</li>
                        <li>TV</li>
                        <li>games</li>
                        <li>videos</li>
                        <li>news</li>
                    </ul>
                </div>

                <div id="col">
                    <h4>dc</h4>
                    <ul>
                        <li>terms of use</li>
                        <li>privacy policy (new)</li>
                        <li>ad choices</li>
                        <li>advertising</li>
                        <li>jobs</li>
                        <li>subscriptions</li>
                        <li>talent workshops</li>
                        <li>CPSC certifications</li>
                        <li>ratings</li>
                        <li>shop help</li>
                        <li>contact us</li>
                    </ul>
                </div>

                <div id="col">
                    <h4>sites</h4>
                    <ul>
                        <li>DC</li>
                        <li>MAD magazine</li>
                        <li>DC kids</li>
                        <li>DC universe</li>
                        <li>DC power visa</li>
                    </ul>
                </div>
                <div id="col">
                    <h4>shop</h4>
                    <ul>
                        <li>shop DC</li>
                        <li>shop DC collectibles</li>

                    </ul>
                </div>

            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
#link-container {
    background-image: url(../assets/img/footer-bg.jpg);
    padding-block: 40px;

    #sect-container {
        width: 60%;
        margin: auto;

        #cols-container {

            width: 50%;
            display: flex;
            flex-direction: row;
            gap: 30px;
            flex-wrap: wrap;

            #col {
                display: flex;
                flex-direction: column;
                gap: 15px;
                color: lightgray;
                width: calc((100% / 3) - (30px));


                h4 {
                    text-transform: uppercase;
                    font-size: 20px;
                }

                ul {
                    display: flex;
                    flex-direction: column;
                    gap: 4px;

                    li {
                        list-style-type: none;
                        text-transform: capitalize;

                    }
                }
            }
        }
    }
}
</style>
