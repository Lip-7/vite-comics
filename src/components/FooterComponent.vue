<template>
    <footer>
        <div class="container d-flex justify-content-between py-4 align-items-center">
            <div class="callToAction p-3">
                <h4 class="text-uppercase mb-0 text-white">Sign-up Now!</h4>
            </div>
            <div class="socials d-flex align-items-center justify-content-between gap-4">
                <h4 class="text-uppercase mb-0">Follow us</h4>
                <div class="socialsIcons d-flex gap-3">
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterComponent'
}
</script>

<style lang="scss" scoped>
footer{
    background-color: #303030;
    .callToAction{
        border: 2px solid #0282F9;
        h4{
            font-size: 1rem;
        }
    }
    .socials{
        h4{
            font-size: 1.4rem;
            color: #0282F9;
        }
    }
}
</style>