<template>
  <div>
  <el-input v-model="input" placeholder="请输入内容"></el-input>
  <el-button icon="el-icon-search" circle></el-button>
    </div>
</template>

<script>
export default {
  name: "Search",
  data() {
    return {
      input1: '',
      input2: '',
      input3: '',
      select: ''
    }
  }
}
</script>

<style scoped>
.el-select .el-input {
    width: 80px;
  }
  .input-with-select .el-input-group__prepend {
    background-color: #fff;
  }
</style>
