<template>
    <section class="preFooter">
        <div class="container py-5 d-flex justify-content-between">
            <div class="linksListWrapper d-flex gap-5">
                <div class="linksList">
                    <h3 class="text-uppercase">dc comics</h3>
                    <ul class=" p-0">
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Video</li>
                        <li>News</li>
                    </ul>
                    <h3 class="text-uppercase">shop</h3>
                    <ul class=" p-0">
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <div class="linksList">
                    <h3 class="text-uppercase">dc</h3>
                    <ul class=" p-0">
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div class="linksList">
                    <h3 class="text-uppercase">sites</h3>
                    <ul class=" p-0">
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>
            <div class="logo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'LinksComponent',

}
</script>

<style lang="scss" scoped>
    .preFooter{
        background-image: url('../assets/img/footer-bg.jpg');
        height: 350px;
        overflow: hidden;
        .linksListWrapper{
            .linksList{
                h3{
                    color: white;
                    font-size: 1.3rem;
                }
                ul{
                    list-style: none;
                    li{
                        color: rgb(138, 138, 138);
                        font-size: .8rem;
                    }
                }
            }
        }
        .logo{
            transform: translateY(-150px);
        }
    }
</style>