<script >
//facciamo l'export
export default {
    name: "FooterSect",
};


</script>

<template>
    <div id="footer-container">
        <a href="">

            <p id="button">sign up now!</p>
        </a>

        <div id="right-sect">
            <p>follow us</p>
            <div id="icons-sect">
                <a href="">

                    <img src="../assets/img/footer-facebook.png" alt="">
                </a>

                <a href="">

                    <img src="../assets/img/footer-twitter.png" alt="">
                </a>

                <a href="">

                    <img src="../assets/img/footer-youtube.png" alt="">
                </a>

                <a href="">

                    <img src="../assets/img/footer-pinterest.png" alt="">
                </a>

                <a href="">

                    <img src="../assets/img/footer-periscope.png" alt="">
                </a>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
#footer-container {
    width: 60%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    padding-block: 30px;
    align-items: center;

    a {
        text-decoration: none;

        #button {
            background-color: #303030;
            border: 1px solid #0282F9;
            color: white;
            text-transform: uppercase;
            padding: 8px;
            font-weight: 600;
        }
    }

    #right-sect {
        display: flex;
        align-items: center;
        gap: 20px;

        p {
            font-weight: 600;
            font-size: 20px;
            text-transform: uppercase;
            color: #0282F9;
        }

        #icons-sect {
            display: flex;
            gap: 10px;
        }
    }
}
</style>
