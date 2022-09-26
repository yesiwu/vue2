<template>
  <div id="a">
    <el-descriptions title="用户信息">
      <el-descriptions-item label="用户名">{{this.$route.params.userName}}</el-descriptions-item>
      <el-descriptions-item label="手机号">18100000000</el-descriptions-item>
      <el-descriptions-item label="居住地">苏州市</el-descriptions-item>
      <el-descriptions-item label="备注">
        <el-tag size="small">学校</el-tag>
      </el-descriptions-item>
      <el-descriptions-item label="联系地址">江苏省苏州市吴中区吴中大道 1188 号</el-descriptions-item>
    </el-descriptions>
  </div>



</template>

<script>
export default {

}
</script>

<style scoped>
#a{
  box-shadow: 0 2px 4px rgba(0, 0, 0, .12), 0 0 6px rgba(0, 0, 0, .04);width: 500px;height: 300px;
  position: absolute;
  left: 500px;
  top:100px;
}
</style>
