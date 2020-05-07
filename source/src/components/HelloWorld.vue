<template>
 <div class="demo-image__lazy" >
  <el-image :src="require('@//assets/1.jpeg')"></el-image>
  <el-image  :src="require('@//assets/2.jpeg')"></el-image>
  <el-image :src="require('@//assets/3.jpeg')"></el-image>
  <el-image :src="require('@//assets/4.jpeg')"></el-image>
  <el-image :src="require('@//assets/5.jpeg')"></el-image>
  <el-image :src="require('@//assets/6.jpeg')"></el-image>
  <el-image :src="require('@//assets/7.jpeg')"></el-image>
</div>
</template>
<style>
.el-carousel__item h3 {
  color: #475669;
  font-size: 18px;
  opacity: 0.75;
  line-height: 300px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
</style>