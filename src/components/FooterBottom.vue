<script>

    export default{
        name: "FooterBottom"
    }

</script>

<template>

    <div class="footer-bottom">
        <div class="container d-flex justify-content-between align-items-center">
            <div>
                <button><strong>SIGN-UP NOW!</strong></button>
            </div>
            <div class="d-flex align-items-center social-link-container">
                <h4>FOLLOW US</h4>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>

    .footer-bottom{
        height: 120px;
        background-color: #303030;


        .container{
            height: 100%;
        }

        button{
            background-color: transparent;
            padding: 1rem;
            border: 2px solid #0282f9;
            color: white;
        }

        h4{
            color:  #0282f9;
        }

        .social-link-container{
            gap: 1rem;
        }
    }

</style>