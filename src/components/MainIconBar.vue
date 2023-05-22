<script>

    export default{
        name: "MainIconBar",
        data(){
            return{
                iconBarItem:[
                    {
                        img: new URL('../assets/img/buy-comics-digital-comics.png', import.meta.url).href,
                        text: "DIGITAL COMICS"
                    },
                    {
                        img: new URL('../assets/img/buy-comics-merchandise.png', import.meta.url).href,
                        text: "DC MERCHANDISE"
                    },
                    {
                        img: new URL('../assets/img/buy-comics-subscriptions.png', import.meta.url).href,
                        text: "SUBSCRIPTIONS"
                    },
                    {
                        img: new URL('../assets/img/buy-comics-shop-locator.png', import.meta.url).href,
                        text: "SHOP LOCATOR"
                    },
                    {
                        img: new URL('../assets/img/buy-dc-power-visa.svg', import.meta.url).href,
                        text: "DC POWER VISA"
                    },
                ]
            }
        }
    }

</script>

<template>

    <div class="main-icon-bar-wrapper">
        <!-- <h2>ICON BAR</h2> -->
        <div class="container d-flex align-items-center">
            <ul class="d-flex justify-content-between">
                <!-- <li class="d-flex align-items-center">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    DIGITAL COMICS
                </li> -->
                <li v-for="item in iconBarItem" class="d-flex align-items-center">
                    <img :src="item.img" alt="">
                    {{ item.text}}
                </li>
            </ul>
        </div>
        
    </div>

</template>

<style lang="scss" scoped>

    .main-icon-bar-wrapper{
        background-color: #0282f9;
        color: white;
        height: 150px;

        div{
            height: 100%;
            padding-left: 2rem;
            padding-right: 2rem;
        }
        
        ul{
            list-style-type: none;
            padding: 0;
            width: 100%;
            height: 100%;

            li{
                height: 100%;
                img{
                    height: 35%;
                    margin-right: 1em;
                }
            }
        }
    }

</style>