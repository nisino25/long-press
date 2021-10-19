<template>
<body   :style="[touching? {backgroundColor: 'BlueViolet'} : {backgroundColor: 'black'}]" @touchstart="touching = true;" @touchend="touching = false">
  <h5 style="color:white; font-size: 200%">Welcome</h5>

</body>

 

</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      // touching: true,
      touching: false,
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
h5{
  padding: 100px 100px;
}
</style>
