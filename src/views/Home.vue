<template>
  <div class="home">
    <div class="header">
      <img class="logo"
           src="../assets/Logo-nav@1x.png">
    </div>
    <div class="row_1">
      <div class="row_1_1">
        <p class="all-caps-text">Influence Global Brands. Get Paid.</p>
        <h1 class="display-4">Get paid for your opinion with branded surveys.</h1>
      </div>
    </div>
    <div class="row_2">

    </div>
    <div class="row_3">

    </div>
    <div class="row_4">

    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>
<style scoped>
.header {
  height: 100px;
}
.logo {
  margin-top: 20px;
  float: left;
  margin-left: 20px;
}
.row_1 {
  background: #eef6fb;
  height: 500px;
}
.row_1_1 {
  float: left;
  padding: 50px;
}
.all-caps-text {
  color: #fd7e14;
}
.row_1 {
  flex: 1;
  justify-content: flex-start;
}
.display-4 {
  width: 300px;
}
.row_2 {
  height: 1000px;
}
.row_3 {
  background: #eef6fb;
  height: 500px;
}
.row_4 {
  background: #eef6fb;
  height: 400px;
}
.trustpilot.visible {
    /* background: url(../img/trust-pilot-bg.png); */
    background-size: cover;
}
</style>
