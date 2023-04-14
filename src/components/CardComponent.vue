<template>
    <div class="wrap">
        <div class="mycard">
            <div class="mycard-img">
                <img :src="thumb" :alt="series">
            </div>
        </div>
        <div class="title">
            <h5>{{ series }}</h5>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CardComponent',
    props: {
        thumb: String,
        price: String,
        series: String,
        type: String,
    },

}
</script>

<style lang="scss" scoped>
.wrap{
    .mycard {
        width: 12rem;
        height: 12rem;
    
        .mycard-img {
            width: 100%;
            height: 100%;
            overflow: hidden;
    
            img {
                width: 100%;
                height: 100%;
                object-position: top;
                object-fit: cover;
            }
        }
    }
    .title{
        width: 12rem;
        h5{
            font-size: 1rem;
            margin-top: .5rem;
        }
    }
}

</style>