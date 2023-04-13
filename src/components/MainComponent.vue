<template>
    <main>
        <div class="container p-4">
            <h2 class="m-3">--Content goes here--</h2>
        </div>
        <BannersComponent/>
    </main>
</template>

<script>
import BannersComponent from './BannersComponent.vue';
export default {
    name: 'MainComponent',
    components: {
        BannersComponent,
    }
}
</script>
<style lang="scss" scoped>
main{
    color: white;
    h2{
    }
}
</style>