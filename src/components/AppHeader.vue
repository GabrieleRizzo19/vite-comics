<script>

    export default{
        name: "AppHeader",
        props: {
            headerLink: Array
        }
    }

</script>

<template>

    <header>
        <div class="header-wrapper container d-flex justify-content-between align-items-center ">
            <div>
                <img src="../assets/img/dc-logo.png" alt="HEADER LOGO">
            </div>
            <div>
                <ul class="d-flex justify-content-between">
                    <!-- <button class="btn">PAGE</button>
                    <button class="btn">PAgsffgGE</button>
                    <button class="btn">PAdfgGE</button>
                    <button class="btn">PAGE</button>
                    <button class="btn">PgAfgdfgGE</button>
                    <button class="btn">PAGE</button>
                    <button class="btn">PAdgfdGE</button>
                    <button class="btn">PAGE</button> -->
                    <li v-for="link in headerLink"><button> {{ link }}</button></li>
                </ul>
            </div>
        </div>
    </header>

</template>

<style lang="scss" scoped>

    header{
        height: 120px;
    }

    .header-wrapper{
        height: 100%;

        ul{
            list-style: none;
        }

        button{
            background-color: transparent;
            font-weight: bold;
            color: grey;
            padding: 1rem;
            cursor: pointer;

            &:hover{
                color: #0282f9;
            }
        }
    }


</style>