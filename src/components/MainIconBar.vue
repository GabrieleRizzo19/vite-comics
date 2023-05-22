<script>

    export default{
        name: "MainIconBar",
        data(){
            return{
                iconBarItem:[
                    {
                        img: '../assets/img/buy-comics-digital-comics.png',
                        text: "DIGITAL COMICS"
                    }
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
                <li class="d-flex align-items-center">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    {{ iconBarItem[0].text }}</li>
                <li>AAAAAAAAA</li>
                <li>AAAAAAAAA</li>
                <li>AAAAAAAAA</li>
                <li>AAAAAAAAA</li>
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
        }
        
        ul{
            list-style-type: none;
            padding: 0;
            width: 100%;
            height: 100%;

            li{
                height: 100%;
                img{
                    height: 50%;
                    margin-right: 1em;
                }
            }
        }
    }

</style>