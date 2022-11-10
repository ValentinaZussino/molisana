<template>
  <HeaderComponent/>
  <main>
  <ProducstList/>
  </main>
  <FooterComponent/>
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import ProducstList from './components/ProducstList.vue';
  export default {
    components: {
    HeaderComponent,
    ProducstList,
    FooterComponent
}
}
</script>

<style lang="scss" scoped>

</style>