<template>
  <div class="view">
    <Header />
    <div class="container">
      <Button />
    </div>
    <Footer />
  </div>
</template>
<script>
import Header from '~/components/organisms/TheHeader.vue'
import Footer from '~/components/organisms/TheFooter.vue'
import Button from '~/components/atoms/AtomButton.vue'

export default {
components: {
    Header,
    Foot,
    Button,
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
