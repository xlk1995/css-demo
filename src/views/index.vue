<template>
  <div>
    <div class="demo">
    </div>
    <div class="demo1">
    </div>
  </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.demo {
  width: 100px;
  height: 150px;
  border: 1px solid red;
  background-color: red;
  background-image: url('../assets/test.jpg');
  background-repeat: no-repeat;
  // background-position: center center;
  background-size: contain;
}
.demo1 {
  width: 800px;
  height: 500px;
  border: 1px solid red;
  // background-color: red;
  // background-image: url('../assets/test.jpg');
  // background-repeat: no-repeat;
  // background-position: center center;
  // background-size: cover;
  background: red url('../assets/test.jpg') no-repeat 0px 0px / contain;
}
</style>