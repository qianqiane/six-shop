<template>
  <div id="app">
    <FooterBar></FooterBar>
    <router-view/>
  </div>
</template>
<script>
  import FooterBar from './components/footerBar'
  export default {
      components:{FooterBar}
  }
</script>
<style lang="less">
html,body{
  height: 100%;
  width: 100% ;
}
</style>
