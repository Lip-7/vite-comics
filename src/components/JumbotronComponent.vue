<template>
    <div class="jumboWrapper">
        <img src="../assets/img/jumbotron.jpg" alt="">
    </div>
</template>

<script>
export default {
    name: 'JumbotronComponent'
}
</script>
<style lang="scss" scoped>
.jumboWrapper{
    height: 400px;
    overflow: hidden;
    img{
        width: 100%;
        object-fit: cover;
    }
}
</style>