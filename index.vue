<template>
  <div>
    <el-tooltip placement="top">
      <img slot="content" :src="src" class="QRcodeSide">
      <span v-text="name"></span>
    </el-tooltip>
  </div>
</template>

<script type="text/ecmascript-6">
  export default {
    data () {
      return {
        aaa: '123',
        content: '1231231'
      }
    },
    props: {
      src: {
        default: ''
      },
      name: {
        default: ''
      }
    }
  }
</script>

<style>
  .QRcodeSide {
    width: 150px;
    height: 150px;
  }
</style>
