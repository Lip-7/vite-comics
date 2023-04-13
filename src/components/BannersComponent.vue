<template>
    <main>
        <div class="banners d-flex justify-content-evenly container py-5">
            <div class="item d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                </div>
                <h4 class="text-uppercase mb-0">Digital Comics</h4>
            </div>
            <div class="item d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                </div>
                <h4 class="text-uppercase mb-0">Dc Merchandise</h4>
            </div>
            <div class="item d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                </div>
                <h4 class="text-uppercase mb-0">subscriptions</h4>
            </div>
            <div class="item d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                <h4 class="text-uppercase mb-0">comics shop locator</h4>
            </div>
            <div class="item d-flex align-items-center gap-3">
                <div class="logo">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                </div>
                <h4 class="text-uppercase mb-0">dc power visa</h4>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: 'BannersComponent',

}
</script>

<style lang="scss" scoped>
main {
    background-color: #0282F9;
    div.banners{
        div.item{
            div.logo{
                width: 3rem;
                height: 3rem;
                img{
                    width: 3.2rem;
                    height: 3.2rem;
                    object-fit: contain;
                }
            }
            h4{
                font-size: 1rem;
                font-weight: 400;
            }
        }
    }
}
</style>