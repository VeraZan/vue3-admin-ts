<template>
  <div class="account">
   <div class="form-wrap">
      <a-form layout="vertical" :model="form">
        <a-form-item>
          <label>用户名</label>
          <a-input />
        </a-form-item>
        <a-form-item>
          <label>密码</label>
          <a-input type="password" />
        </a-form-item>
        <a-form-item>
          <a-button type="primary" block>
            登录
          </a-button>
        </a-form-item>
      </a-form>
      <div class="text-center fs-12 color-white">
        <a class="color-white">忘记密码</a> | 
        <a class="color-white">注册</a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "Login",
  setup(props){

  }
});
</script>
<style lang="scss">
@import "./style.scss";
</style>
