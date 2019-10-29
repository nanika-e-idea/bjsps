<template>
  <div class="view">
    <Button />
  </div>
</template>
<script>
import Button from '~/components/atoms/AtomButton.vue'

export default {
components: {
    Button
  }
}
</script>
<style scoped>
.view{
  box-sizing: border-box;
  width: 100%;
  padding: 20px;
  height: auto;
  background-color: #acd;
}
</style>
