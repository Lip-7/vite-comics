<template>
  <HeaderComponent/>
  <MainComponent/>
  <LinkssComponentVue/>
  <FooterComponent></FooterComponent>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue'
import LinkssComponentVue from './components/LinkssComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
export default {
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
    LinkssComponentVue
  },
  data() {
    return {
      
    }
  }
}
</script>

<style lang="scss" scoped></style>