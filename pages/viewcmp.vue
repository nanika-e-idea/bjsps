<template>
  <div class="view">
    <Header />
    <div class="container">
      <View />
    </div>
    <Footer />
  </div>
</template>
<script>
import Header from '~/components/organisms/TheHeader.vue'
import Footer from '~/components/organisms/TheFooter.vue'
import View from '~/components/molecules/MolForm.vue'

export default {
components: {
    Header,
    Footer,
    View,
  }
}
</script>
<style scoped>
.container{
  box-sizing: border-box;
  width: 100%;
  padding: 20px;
  height: auto;
  background-color: #acd;
}
</style>
