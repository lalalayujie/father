<template>
  <div class="body">
    <div class="wenzi">称呼：钟先生</div>
    <div class="wenzi">电话：13788648815</div>
    <div class="wenzi">微信：zLA888036</div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.body {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: linear-gradient(to right, rgb(248, 176, 188), rgb(125, 223, 247));
}

.wenzi {
  font-size: 25px;
  margin: 7px;
  color: aliceblue;
}
</style>
