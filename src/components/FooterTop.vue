<script>

    export default{
        name: "FooterTop"
    }

</script>


<template>

    <div class="footer-top">
        <div class="container pos-relative">
            <div class="d-flex">
                <div class="footer-top-column">
                    <strong class="footer-list-title">DC COMICS</strong>
                    <ul>
                        <li><small><a href="">Characters</a></small></li>
                        <li><small><a href="">Comics</a></small></li>
                        <li><small><a href="">Movies</a></small></li>
                        <li><small><a href="">TV</a></small></li>
                        <li><small><a href="">Games</a></small></li>
                        <li><small><a href="">Videos</a></small></li>
                        <li><small><a href="">News</a></small></li>
                    </ul>
                    <strong class="footer-list-title">SHOP</strong>
                    <ul>
                        <li><small><a href="">Shop DC</a></small></li>
                        <li><small><a href="">Shop DC Collectibles</a> </small></li>
                    </ul>
                </div>
                <div class="footer-top-column">
                    <strong class="footer-list-title">DC</strong>
                    <ul>
                        <li><small><a href="">Terms Of Use</a></small></li>
                        <li><small><a href="">Privacy policy (New)</a></small></li>
                        <li><small><a href="">Ad Choices</a></small></li>
                        <li><small><a href="">Advertising</a></small></li>
                        <li><small><a href="">Jobs</a> </small></li>
                        <li><small><a href="">Subscriptions</a></small></li>
                        <li><small><a href="">Talent Workshops</a></small></li>
                        <li><small><a href="">CPSC Certificates</a></small></li>
                        <li><small><a href="">Ratings</a></small></li>
                        <li><small><a href="">Shop Help</a></small></li>
                        <li><small><a href="">Contact Us</a></small></li>
                    </ul>
                </div>
                <div class="footer-top-column">
                    <strong class="footer-list-title">SITES</strong>
                    <ul>
                        <li><small><a href="">DC</a></small></li>
                        <li><small><a href="">MAD Magazine</a></small></li>
                        <li><small><a href="">DC Kids</a></small></li>
                        <li><small><a href="">DC Universe</a></small></li>
                        <li><small><a href="">DC Power Visa</a></small></li>
                    </ul>
                </div>
            </div>
            <img class="pos-absolute" src="../assets/img/dc-logo-bg.png" alt="">
        </div> 
    </div>

</template>

<style lang="scss" scoped>

    .footer-top{
        height: 380px;
        background-image: url('../assets/img/footer-bg.jpg');
        color: white;
        padding-top: 2rem;
        overflow: hidden;

        .footer-top-column{
            margin-right: 2rem;
        }

        ul{
            list-style-type: none;
            padding: 1rem 0;

            small{
                color: grey;
            }
        }

        .footer-list-title{
            margin-bottom: 5rem;
        }

        a{
            text-decoration: none;
            color: inherit;

            &:hover{
                color: white;
            }
        }

        img{
            right: 0;
            top: 50%;
            transform: translateY(-50%);
        }
    }

</style>