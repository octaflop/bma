<template>
  <div id="app">
    <b-container class="bv-example-row">
      <b-row>
        <b-col>
          1 of 4
        </b-col>
        <b-col>
          2 of 4
        </b-col>
        <b-col>
          3 of 4
        </b-col>
        <b-col>
          4 of 4
        </b-col>
      </b-row>
    </b-container>
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
