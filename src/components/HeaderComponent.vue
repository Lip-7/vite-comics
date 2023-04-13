<template>
    <header class="bg-white mt-4">
        <div class="container d-flex justify-content-between">
            <div class="logo d-flex align-items-center">
                <a href="#"><img src="../assets/img/dc-logo.png" alt=""></a>
            </div>
            <ul class="d-flex justify-content-between gap-2">
                <li class="text-uppercase"><a href="#">Characters</a></li>
                <li class="text-uppercase active"><a href="#">Comics</a></li>
                <li class="text-uppercase"><a href="#">Movies</a></li>
                <li class="text-uppercase"><a href="#">Tv</a></li>
                <li class="text-uppercase"><a href="#">Games</a></li>
                <li class="text-uppercase"><a href="#">Collectibles</a></li>
                <li class="text-uppercase"><a href="#">Videos</a></li>
                <li class="text-uppercase"><a href="#">Fans</a></li>
                <li class="text-uppercase"><a href="#">News</a></li>
                <li class="text-uppercase"><a href="#">Shop</a></li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent',

}
</script>
    
<style lang="scss" scoped>
@use '../assets/styles/partials/variables.scss';
header {
    .logo{
        width: 5rem;
        img{
            width: 100%;
        }
    }
    ul {
        margin-bottom: 0;
        list-style: none;
        li{
            margin: 0 5px;
            padding: 50px 0 47px 0;
            font-weight: 600;
            color: black;
            border-bottom: 3px solid transparent;
            cursor: pointer;
            &.active{
                border-bottom: 3px solid #0C7CEC;
                color: #0C7CEC;
            }
            &.active a{
                color: #0C7CEC;
            }
            &:hover a{
                color: #0C7CEC;
            }
            a{
                text-decoration: none;
                color: black;
            }
        }
    }
}

</style>