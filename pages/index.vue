<template>
  <div>
    <h1>Hello World</h1>
    <el-button
      @click="$notify({title:'hello', message: 'World'})"
    >

      Default
    </el-button>
  </div>
</template>

<script>

export default {
  components:{
  }
}
</script>

<style>
</style>
