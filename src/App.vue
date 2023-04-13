<template>
  <HeaderComponent/>
  <MainComponent/>
  <LinksComponent/>
  <FooterComponent></FooterComponent>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue'
import LinksComponent from './components/LinksComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
export default {
  components: {
    HeaderComponent,
    MainComponent,
    LinksComponent,
    FooterComponent,
  }
}
</script>

<style lang="scss" scoped></style>