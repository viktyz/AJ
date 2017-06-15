<template>
  <div class="homepage">
    <div class="headsection"></div>
    <div class="secondsection"></div>
    <div class="thirdsection"></div>
    <div class="tailsection"></div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .homepage{
    width: 100%;
    height: 100%;
  }
  .headsection{
    width: 100%;
    height: 60px;
    flex-direction: row;
    background-color: red;
  }
  .secondsection{
    width: 100%;
    background-color: blue;
  }
  .thirdsection{
    width: 100%;
    height: 410px;
    background-color: green;
  }
  .tailsection{
    width: 100%;
    height: 230px;
    margin-bottom: 0px;
    background-color: gray;
  }

</style>
