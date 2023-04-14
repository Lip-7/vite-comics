<template>
    <main>
        <JumbotronComponent/>
        <div class="container p-4">
            <div class="currentSeries p-3">
                <h3 class="text-uppercase mb-0">current Series</h3>
            </div>
            <!-- <h2 class="m-3">--Content goes here--</h2> -->
            <div class="cardsContainer d-flex flex-wrap justify-content-center gap-4">
                <CardComponent :thumb="com.thumb" :price="com.price" :series="com.series" :type="com.type" v-for="com in comicsArray"/>
            </div>
        </div>
        <BannersComponent/>
    </main>
</template>

<script>
import { comics } from "../assets/data/data.js";
import JumbotronComponent from './JumbotronComponent.vue';
import CardComponent from './CardComponent.vue';
import BannersComponent from './BannersComponent.vue';
export default {
    name: 'MainComponent',
    components: {
        BannersComponent,
        CardComponent,
        JumbotronComponent,
    },
    data() {
        return {
            comicsArray: [...comics],
        }
    }
}
</script>
<style lang="scss" scoped>
@import '../assets/styles/partials/variables';
main{
    color: white;
    .currentSeries{
        background-color: $logoColor;
        width: fit-content;
        transform: translateY(-55px);
    }
}
</style>