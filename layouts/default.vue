<template>
  <div class="main">
    <div class="row">
      <side-bar></side-bar>
      <div>
      <header-panel></header-panel>
      <nuxt>
        
      </nuxt>
      </div>
      
    </div>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
.main{
  
}
.main>.row{
  box-sizing:border-box;
  display:flex;
  flex-direction:row;
  justify-content:flex-start;
  width:100%;
}
.main .row>div:first-child{
  width:40%;
}
.main .row>div:last-child{
  width:60%;
}
</style>
<script>
import SideBar from '~/components/panel/SideBar.vue'
import HeaderPanel from '~/components/panel/HeaderPanel.vue'
export default {
  components: {
    SideBar,
    HeaderPanel
  }
}
</script>

