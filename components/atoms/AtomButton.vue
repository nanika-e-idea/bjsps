<template>
<button class="button">
  <div class="buttonIcon">
    <img v-if="entryVal['icon']" />
  </div>
  <span class="buttonLabel"><v-html="entryVal['labrl']"></span>
</button>
</template>
<script>
export default{
  name: 'Button',
  props: {
    data: Array,
  },
  computed: {
    iterationData() {
      let data = this.data
      return data
    }
  },
}
</script>
<style rang="scss">
.button{
  box-sizing: border-box;
  width: auto;
  max-width: 90%;
  min-width: 200px;
  height: 40px;
  margin: 0;
  padding: 0 10px;
  border: solid 1px #777;
  border-radius: 20px;
  border-color: #777;
  background-color: rgba(255,255,255,0.5);
  overflow: hidden;
}
.buttonIcon{
  box-sizing: border-box;
  width: 20px;
  height: 20px;
  margin: 5px;
  padding: 0;
  float: left;
  font-size: 20px;
  line-height: 20px;
  border: solid 1px #777;
}
.buttonLabel{
  font-size: 14px;
  line-height: 30px;
  color: #777;
}
</style>
