<template>
  <div class="header-container">
    <div class="header max-w-screen-lg mx-auto">
      <div class="top-bar flex justify-between p-2">
        <div class="contact font-semibold">
          Hotline: <span class="phone-number">0963 323 650</span> | Email:
          <span class="phone-number">cskh@123train.vn</span>
        </div>
        <div class="top-bar-right flex justify-between">
          <div class="social"></div>
          <div class="language flex">
            Việt Nam
            <img
              src="data:image/svg+xml;base64,PHN2ZyBpZD0iaWNvbi1mbGFnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxyZWN0IGlkPSJSZWN0YW5nbGVfOSIgZGF0YS1uYW1lPSJSZWN0YW5nbGUgOSIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSJub25lIiAvPgogICAgPGcgaWQ9Ikdyb3VwXzgiIGRhdGEtbmFtZT0iR3JvdXAgOCIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMyAtODIuMjUpIj4KICAgICAgICA8cGF0aCBpZD0iUGF0aF8xIiBkYXRhLW5hbWU9IlBhdGggMSIKICAgICAgICAgICAgZD0iTTE2LjY1Nyw4OC4yNUgxLjM0N0ExLjM0NywxLjM0NywwLDAsMCwwLDg5LjZ2OS4xYTEuMzQ3LDEuMzQ3LDAsMCwwLDEuMzQ3LDEuMzQ3SDE2LjY1M0ExLjM0NywxLjM0NywwLDAsMCwxOCw5OC43Vjg5LjZBMS4zNDIsMS4zNDIsMCwwLDAsMTYuNjU3LDg4LjI1WiIKICAgICAgICAgICAgZmlsbD0iI2ZmNGI1NSIgLz4KICAgICAgICA8cGF0aCBpZD0iUGF0aF8yIiBkYXRhLW5hbWU9IlBhdGggMiIKICAgICAgICAgICAgZD0iTTE1My4yMSwxNTMuMDY3bC44MywyLjQ5LDIuNjIzLjAyMWEuMTUxLjE1MSwwLDAsMSwuMDg4LjI3NGwtMi4xMSwxLjU1OC43OTEsMi41YS4xNTIuMTUyLDAsMCwxLS4yMzYuMTY5bC0yLjEzMS0xLjUyMy0yLjEzNCwxLjUyNmEuMTU0LjE1NCwwLDAsMS0uMjM2LS4xNjlsLjc5MS0yLjUtMi4xMS0xLjU1OGEuMTUyLjE1MiwwLDAsMSwuMDg4LS4yNzRsMi42MjMtLjAyMS44My0yLjQ5QS4xNTMuMTUzLDAsMCwxLDE1My4yMSwxNTMuMDY3WiIKICAgICAgICAgICAgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTE0NC4wNjQgLTYyLjQzNykiIGZpbGw9IiNmZmUxNWEiIC8+CiAgICA8L2c+Cjwvc3ZnPg=="
              alt="VN"
            />
          </div>
        </div>
      </div>

      <div class="header-content p-2.5 flex min-w-full">
        <img
          src="https://123train.vn/_nuxt/img/logo-header.63eff83.svg"
          alt="logo"
          class="mr-4"
        />
        <div class="header-content-menu flex justify-between items-center">
          <div class="nav flex">
            <a href="#" class="nav-item">Trang chủ</a>
            <a href="#" class="nav-item">Sản phẩm</a>
            <a href="#" class="nav-item">Ngành hàng</a>
            <a href="#" class="nav-item">Bảng giá</a>
            <a href="#" class="nav-item">Về chúng tôi</a>
            <a href="#" class="nav-item">Liên hệ</a>
          </div>
          <div class="try-free flex my-2.5 items-center">
            <div class="login">Đăng nhập</div>
            <div class="register">Đăng ký dùng thử</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.header-container {
    box-shadow: 0 2px 4px rgb(45 62 80 / 12%)
}

.top-bar .phone-number {
  color: #f57b20;
}

.nav-item {
  line-height: 19px;
  font-size: 14px;
  color: #00000080;
  padding: 10px 15px;
  font-weight: 500;
}

.header-content-menu {
  flex: 90%;
}

.try-free {
  font-weight: 600;
}

.try-free .login {
  font-size: 18px;
  margin-right: 15px;
  color: #007bff;
}

.try-free .register {
  color: white;
  font-weight: 700;
  font-size: 16px;
  border: 1px solid #f57b20;
  border-radius: 5px;
  background: #f57b20;
  padding: 9px 12px;
  transition: all 0.2s linear; 
}

.register:hover {
    cursor: pointer;
    color: #f57b20;
    background: white;
}

</style>
