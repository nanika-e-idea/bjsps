<template>
  <div id="footer">
    <div class="f-nav">
      <ul class="f-nav-items">
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
      </ul>
    </div>
    <div class="f-end">
        <span>copylight...</span>
    </div>
  </div>
</template>
<style lang="scss">
#footer{
  width: 100%;
  text-align: center;
}
.f-nav-items{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  width: 90%;
  max-width: 1200px;
  margin: auto;
  li{
    width: 90px;
    line-height: 1rem;
    font-size: 0.8rem;
    text-align: center;
    border-left: solid 1px #777;
    &:last-child{
      border-right: solid 1px #777;
    }
  }
}
.f-end{
  width: 100%;
    line-height: 2rem;
    font-size: 0.8rem;
    text-align: center;
  background-color: #777;
}
</style>
