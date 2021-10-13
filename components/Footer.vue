<template>
  <div class="footer pt-6">
    <div class="footer-top-container py-4">
      <div class="footer-top flex max-w-screen-lg mx-auto">
        <div class="footer-col footer-col-30">
          <img
            src="https://123train.vn/_nuxt/img/logo_white.126368c.png"
            alt="logo"
            class="py-4"
          />
          <div class="footer-info">
            <h4 class="title-info font-semibold py-2">
              CÔNG TY CỔ PHẦN TECHCEN
            </h4>
            <p class="text-info">
              <span
                >Tầng 3 toà G1, FiveStar Garden, số 2 Kim Giang, Thanh Xuân, Hà
                Nội</span
              >
            </p>
            <p class="text-info">Email: <span>cskh@123train.vn</span></p>
            <p class="text-info">SĐT: <span>0963 323 650</span></p>
            <p class="text-info">ĐKKD: <span>0109519280</span></p>
          </div>
        </div>
        <div class="footer-col footer-col-40 p-2.5 ml-3">
          <h3 class="footer-title">Liên kết nhanh</h3>
          <div class="flex flex-row">
            <div class="footer-link-content flex flex-col">
              <a href="#" class="link">Trang chủ</a>
              <a href="#" class="link">Elearning cho doanh nghiệp</a>
              <a href="#" class="link">Elearning cho giảng viên</a>
              <a href="#" class="link">Các ngành hàng</a>
              <a href="#" class="link">Bảng giá</a>
              <a href="#" class="link">Giới thiệu về 123Train</a>
            </div>
             <div class="footer-link-content pl-2 flex flex-col">
              <a href="#" class="link">Tin tức</a>
              <a href="#" class="link">Tuyển dụng</a>
              <a href="#" class="link">Liên hệ</a>
            </div>
          </div>
        </div>
        <div class="footer-col footer-col-30">
            <div class="fanpage">
                <img src="" alt="fanpage" width="100%" height="200px">
            </div>
        </div>
      </div>
    </div>

    <div class="footer-bottom-container font-bold">
      <div
        class="
          footer-bottom
          flex
          justify-between
          max-w-screen-lg
          mx-auto
          py-2.5
        "
      >
        <h4 class="coppy-right">
          Coppyright ©2021 TECHCEN. All Right Reserved.
        </h4>
        <h4 class="coppy-right">
          <a href="" class="footer-bottom-link">Điều khoản sử dụng</a>
          <a href="" class="footer-bottom-link">Chính sách bảo mật</a>
          <a href="" class="footer-bottom-link">Chính sách thanh toán</a>
        </h4>
      </div>
    </div>
  </div>
</template>

<style scoped>
.footer-top-container {
  background: rgb(49, 55, 74);
}

.footer-top {
  color: white;
}

.title-info {
  font-size: 18px;
}

.footer-top span {
  font-weight: 700;
}

.footer-col-30 {
  width: 30%;
}

.footer-col-40 {
  width: 40%;
}

.text-info + .text-info {
  margin-top: 12px;
}

h3.footer-title {
    font-size: 24px;
    font-weight: bolder;
    padding-bottom: 18px; 
}

.footer-link-content {
    width: 50%;
}

.footer-link-content a {
    margin-bottom: 10px;
    font-weight: 600;
}

/* footer-bottom */
.footer-bottom-container {
  background: rgb(42, 47, 62);
  font-size: 14px;
  color: white;
}

.footer-bottom-link {
  padding: 0 4px;
}

.footer-bottom-link + .footer-bottom-link {
  border-left: 2px solid white;
}
</style>
