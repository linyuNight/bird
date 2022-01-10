<template>
  <div class="home" v-if="$route.query.aaa === '123'">
    <div>姓名：林煜</div>
    <div>性别：男</div>
    <div>年龄：31岁</div>
    <div>职业：程序员</div>
    <div>学历：本科</div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  data() {
    return {
      isShow: false
    }
  },
  created() {
    console.log(this.$route)
  }
}
</script>
