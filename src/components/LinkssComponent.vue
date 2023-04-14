<template>
    <section class="preFooter">
        <div class="container py-5 d-flex justify-content-between">
            <div class="linksListWrapper d-flex gap-5">
                <div class="linksList">
                    <h3 class="text-uppercase">dc comics</h3>
                    <ul class=" p-0">
                        <a href="#">
                            <li>Characters</li>
                        </a>
                        <a href="#">
                            <li>Comics</li>
                        </a>
                        <a href="#">
                            <li>Movies</li>
                        </a>
                        <a href="#">
                            <li>TV</li>
                        </a>
                        <a href="#">
                            <li>Games</li>
                        </a>
                        <a href="#">
                            <li>Video</li>
                        </a>
                        <a href="#">
                            <li>News</li>
                        </a>
                    </ul>
                    <h3 class="text-uppercase">shop</h3>
                    <ul class=" p-0">
                        <a href="#">
                            <li>Shop DC</li>
                        </a>
                        <a href="#">
                            <li>Shop DC Collectibles</li>
                        </a>
                    </ul>
                </div>
                <div class="linksList">
                    <h3 class="text-uppercase">dc</h3>
                    <ul class=" p-0">
                        <a href="#">
                            <li>Terms Of Use</li>
                        </a>
                        <a href="#">
                            <li>Privacy policy (New)</li>
                        </a>
                        <a href="#">
                            <li>Ad Choices</li>
                        </a>
                        <a href="#">
                            <li>Advertising</li>
                        </a>
                        <a href="#">
                            <li>Jobs</li>
                        </a>
                        <a href="#">
                            <li>Subscriptions</li>
                        </a>
                        <a href="#">
                            <li>Talent Workshops</li>
                        </a>
                        <a href="#">
                            <li>CPSC Certificates</li>
                        </a>
                        <a href="#">
                            <li>Ratings</li>
                        </a>
                        <a href="#">
                            <li>Shop Help</li>
                        </a>
                        <a href="#">
                            <li>Contact Us</li>
                        </a>
                    </ul>
                </div>
                <div class="linksList">
                    <h3 class="text-uppercase">sites</h3>
                    <ul class=" p-0">
                        <a href="#">
                            <li>DC</li>
                        </a>
                        <a href="#">
                            <li>MAD Magazine</li>
                        </a>
                        <a href="#">
                            <li>DC Kids</li>
                        </a>
                        <a href="#">
                            <li>DC Universe</li>
                        </a>
                        <a href="#">
                            <li>DC Power Visa</li>
                        </a>
                </ul>
            </div>
        </div>
        <div class="logo">
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
</section></template>

<script>
export default {
    name: 'LinkssComponent',

}
</script>

<style lang="scss" scoped>.preFooter {
    background-image: url('../assets/img/footer-bg.jpg');
    height: 350px;
    overflow: hidden;

    .linksListWrapper {
        a {
            text-decoration: none;

        }

        .linksList {
            h3 {
                color: white;
                font-size: 1.3rem;
            }

            ul {
                list-style: none;

                li {
                    color: rgb(138, 138, 138);
                    font-size: .8rem;
                    &:hover {
                        color: rgb(183, 183, 183);
                    }
                }
            }
        }
    }

    .logo {
        transform: translateY(-150px);
    }
}</style>