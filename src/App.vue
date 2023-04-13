<template>
  <HeaderComponent/>
  <MainComponent/>
  <LinksComponent/>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue'
import LinksComponent from './components/LinksComponent.vue';
export default {
  components: {
    HeaderComponent,
    MainComponent,
    LinksComponent,
  }
}
</script>

<style lang="scss" scoped></style>