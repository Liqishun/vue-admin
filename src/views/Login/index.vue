<template>
  <div id="login">
    <el-button disabled>默认按钮</el-button>
    <el-button type="primary" disabled>主要按钮</el-button>
    <el-button type="success" disabled>成功按钮</el-button>
    <el-button type="info" disabled>信息按钮</el-button>
    <el-button type="warning" disabled>警告按钮</el-button>
    <el-button type="danger" disabled>危险按钮</el-button>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },

  methods: {}
};
</script>
<style lang="scss" scoped>
#login {
  height: 50vh;
  background-color: aqua;
}
</style>
