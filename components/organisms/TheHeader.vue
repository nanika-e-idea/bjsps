<template>
  <div id="header">
    <div class="h-logo"></div>
    <div class="h-nav">
      <ul class="h-nav-items">
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
      </ul>
    </div>
    <div class="h-nav_sp">
      <ul class="h-nav_sp-items">
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
        <li>navi</li>
      </ul>
    </div>
  </div>
</template>
<style lang="scss">
#header{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  width: 100%;
  text-align: center;
}
.h-logo{
  width: 10%;
  heighht: auto;
  max-width: 100px;
  min-height: 50px;
  border: solid 1px #777;
}
.h-nav-items{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  width: 90%;
  max-width: 1200px;
  margin: auto;
  li{
    width: 120px;
    line-height: 2rem;
    font-size: 1rem;
    font-weight: 600;
    text-align: center;
    border-left: solid 1px #777;
    &:last-child{
      border-right: solid 1px #777;
    }
  }
}
.h-nev_sp{
  display: none;
  width: 0;
  height: 0;
  overflow: hidden;
}
</style>
