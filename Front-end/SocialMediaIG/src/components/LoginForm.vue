<script setup lang="ts">

</script>

<template>
  <a-row justify="center" align="middle" style="min-height: 98vh;">
    <a-col>
      <!-- Login Form -->
      <a-card>
        <i data-visualcompletion="css-img" aria-label="Instagram" class="css-img" role="img"></i>
        <a-form layout="vertical">
          <a-form-item name="username" rules="[{ required: true, message: 'Please enter your username!' }]">
            <a-input placeholder="Số điện thoại, tên người dùng hoặc email" />
          </a-form-item>
          <a-form-item name="password" rules="[{ required: true, message: 'Please enter your password!' }]">
            <a-input-password placeholder="Mật khẩu" />
          </a-form-item>

          <a-form-item>
            <a-button type="primary" block>Đăng nhập</a-button>
          </a-form-item>
        </a-form>

        <a-link href="#" style="display: block; text-align: center;">
          Quên mật khẩu?
        </a-link>
      </a-card>

      <!-- Sign Up Link -->
      <a-card style="margin-top: 24px; text-align: center;">
        <span>Bạn chưa có tài khoản?</span>
        <a-link href="#">Đăng ký</a-link>
      </a-card>

      <!-- App Download Links -->
      <div style="text-align: center; margin-top: 16px;">
        <p>Tải ứng dụng.</p>
        <div>
          <a href="https://play.google.com" target="_blank">
            <img
              src="https://static.cdninstagram.com/rsrc.php/v3/y2/r/yKDBMIG1og3.png"
              alt="Google Play"
              style="width: 135px; height: 40px; margin-right: 8px;"
            />
          </a>
          <a href="https://www.microsoft.com" target="_blank">
            <img
              src="https://static.cdninstagram.com/rsrc.php/v3/ys/r/0evRgTlaFrn.png"
              alt="Microsoft Store"
              style="width: 110px; height: 40px"
            />
          </a>
        </div>
      </div>
    </a-col>
  </a-row>
</template>

<style scoped lang="scss">
.css-img {
  background-image: url('https://static.cdninstagram.com/rsrc.php/v3/yM/r/8n91YnfPq0s.png');
  background-position: 0px -52px;
  background-size: auto;
  width: 175px;
  height: 51px;
  background-repeat: no-repeat;
  display: inline-block;
}
</style>