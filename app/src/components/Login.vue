<template>
    <div>
        <h3>路人甲：会员登录</h3>
        <input type="text" placeholder="请输入用户名">
        <input type="password" placeholder="请输入密码">
        <br>
        <button class="login-btn">登录</button>
    </div>
</template>

<script>
    export default {
        name: "Login"
    }
</script>

<style scoped>
.login-btn{margin-top: 10px}
</style>