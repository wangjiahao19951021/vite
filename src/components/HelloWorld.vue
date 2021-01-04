<template>
  <h1>{{ msg }}</h1>
  <p>Edit <code>components/HelloWorld.vue</code> to test hot module replacement.</p>
  <div class="rows">
    <el-button @click="count++">{{ count }}</el-button>
  </div>
  <div class="cehsi">测试</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
<style lang="scss" scoped>
.cehsi{
  color: $red;
}
</style>