<template>
  <el-container>
    <!-- 登录页面页头区域 -->
    <el-header>{{ applicationName }}</el-header>
    <!-- 登录页面主体内容区域 -->
    <el-main>
      <!-- 头像昵称区域 -->
      <div>
        <el-avatar v-bind:src="userInfo.avatarSrc"></el-avatar>
        
      </div>
    </el-main>
    <!-- 登录页面页脚区域 -->
    <el-footer></el-footer>
  </el-container>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      applicationName: 'Hi顺带帮帮我',
      userInfo: {
        avatarSrc: 'https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png'
      }
    }
  }
}
</script>
