<template>
  <div class="login min-width-wrapper">
    <div class="login-wrapper">
      <img class="logo" src="../../img/logo.png"/>
      <div class="login-box clearfix">
        <div class="login-index pull-left">
        </div>
        <img class="login-images pull-right" src="../../img/zt.png"/>
      </div>
      <p class="copyright">Copyright © 2016 国脉海洋信息发展有限公司</p>
    </div>
  </div>
</template>
<script>
export default {
  data () {
    return {}
  }
}
</script>

<style scoped lang="scss">
.login {
  position: relative;
  width: 100%;
  height: 100vh;
  min-height: 620px;
  text-align: center;
  background: linear-gradient(#015293 50%, #fff 50%);
  .login-wrapper {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-left: -359px;
    margin-top: -250px;
    .logo{
      width: 351px;
      height: 56px;
    }
    .login-box{
      border-radius: 10px;
      margin: 30px auto;
      width: 718px;
      height: 350px;
      background: #fff;
      box-shadow: 2px 2px 2px #888888;
    }
    .login-images{
      padding: 40px 60px 40px 0;
    }
    .copyright {
      color: #444;
      font-size: 14px;
    }
    .login-form {
      padding: 60px 0 40px 60px;
      .el-input__inner {
        width: 300px;
      }
      .login-btn {
        border: 0;
        width: 300px;
        background: #015293;
        &:hover {
          background: #0060ad;
        }
      }
      .captcha-input {
        vertical-align: middle;
        .el-input__inner {
          width: 200px;
        }
        &.el-input {
          width: 200px;
        }
      }
      .yz {
        cursor: pointer;
        width: 96px;
        height: 36px;
        border-radius: 4px;
        vertical-align: middle;
      }
    }
  }
}
</style>
