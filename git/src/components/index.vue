<template>
    <div class='index'>
        <router-link to="/login" tag='span'>手机号登录</router-link>
        <router-link to="/register" tag='span'>注册</router-link>
    </div>
</template>
<script>
export default {
    name:'index'
}
</script>
<style >
.index{
  width:100%;
  height:100%;
  display: flex;
  flex-direction: column;
}
span{
    width:80%;
    height:40px;
    line-height:40px;
    margin-top:20px;
    margin-left:10%;
    border:1px solid #f00;
    border-radius:30px;
    text-align: center;
}
</style>