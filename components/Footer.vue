<template>
  <footer class="footer">
    <!-- <img src="~/assets/img/bill-img-3.png" alt=""> -->
    <b-scontainer class="bv-example-row">
      <b-row>
        <b-col>
          <ul>
            <li><h4 class="has-text-weight-bold">تطبيقات الهواتف</h4></li>
            <li>
              <div class="row">
                <div class="col">
                  <div class="towImages">
                    <img src="~/assets/img/addons2.png" alt="" /><img
                      src="~/assets/img/addons3.png"
                      alt=""
                    />
                  </div>
                </div>
                <div class="col">
                  <div>
                    <img class="Qr" src="~/assets/img/qr-code.png" alt="" />
                  </div>
                </div>
              </div>
            </li></ul
        ></b-col>
        <b-col>
          <ul>
            <li><h4 class="has-text-weight-bold">القائمة البريدية</h4></li>
            <li>
              <p>
                أدخل البريد الإلكتروني الخاص بك لتلقي آخر الأخبار عن الموقع
                والمنتجات الجديدة
              </p>
            </li>
            <li>
              <b-input-group>
                <b-input-group-prepend>
                  <b-button variant="dark">ارسال</b-button>
                </b-input-group-prepend>

                <b-form-input type="text" min="0.00"></b-form-input>
              </b-input-group>
            </li></ul
        ></b-col>
        <b-col>
          <ul>
            <li><nuxt-link to="/" class="link">من نحن</nuxt-link></li>
            <li><nuxt-link to="/" class="link">الشحن والتوصيل</nuxt-link></li>
            <li><nuxt-link to="/" class="link">طرق الدفع</nuxt-link></li>
            <li><nuxt-link to="/" class="link">شروط الاستخدام</nuxt-link></li>
            <li><nuxt-link to="/" class="link">سياسه الخصوصية</nuxt-link></li>
          </ul>
        </b-col>
        <b-col>
          <div class="row">
            <div class="col">
              <ul>
                <li><nuxt-link to="/" class="link">الرئيسيه</nuxt-link></li>
                <li><nuxt-link to="/" class="link">الفروع</nuxt-link></li>
                <li><nuxt-link to="/" class="link">مكتب النشر</nuxt-link></li>
                <li><nuxt-link to="/" class="link">القسام</nuxt-link></li>
                <li><nuxt-link to="/" class="link">اتصل بنا</nuxt-link></li>
              </ul>
            </div>
            <div class="col">
              <nuxt-link to="/">
                <figure class="figure image is-128x128">
                  <img
                    class="footerImage"
                    src="~/assets/img/footer_logo.png"
                    alt="إيراد المتحدة"
                  />
                </figure>
              </nuxt-link>
            </div>
          </div>
        </b-col>
      </b-row>
    </b-scontainer>
    <div class="footer-end">
      <div class="columns">
        <div class="column is-8">
          <p>© 2018 جميع الحقوق محفوظة | برمجة و تصميم : مربع</p>
        </div>
        <div class="column is-4">
          <ul class="social-media-footer">
            <li>
              <a href="https://wa.me/920017780" class="hvr-grow-shadow">
                <i class="fab fa-whatsapp"></i>
              </a>
            </li>
            <li>
              <a href="" class="hvr-grow-shadow">
                <i class="fab fa-facebook-square"></i>
              </a>
            </li>
            <li>
              <a href="" class="hvr-grow-shadow">
                <i class="fab fa-instagram"></i>
              </a>
            </li>
            <li>
              <a href="" class="hvr-grow-shadow"
                ><i class="fab fa-pinterest"></i
              ></a>
            </li>
            <li>
              <a href="" class="hvr-grow-shadow"
                ><i class="fab fa-vimeo-v"></i
              ></a>
            </li>
            <li>
              <a
                href="http://asdcoagro.com/webmail"
                target="_blank"
                class="hvr-grow-shadow mail-icon"
              >
                <i class="fas fa-envelope"></i>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<style scoped>
footer {
  background-color: #f5f3f3;
  padding: 3rem 3rem 0.5rem;
}
.footer-end {
  padding: 0 20px;
  margin-top: 20px;
  border-bottom: 53px solid #e9e4e4;
  border-left: 50px solid transparent;
  border-right: 50px solid transparent;
  height: 0;
}
.link {
  color: #1a1e1c;
  font-weight: 700;
  display: block;
  line-height: 30px;
  font-size: 14px;
  text-decoration: none;
}
.link:hover {
  color: #329e5d;
}
ul {
  text-align: right;
}
li {
  list-style: none;
}
.footerImage {
  width: 125px;
  height: 125px;
  display: inline-block;
}
.towImages img {
  width: 100px;
  display: block;
}
.Qr {
  width: 85px;
}
.hvr-grow-shadow i {
  color: #000;
  font-size: 20px;
}
.social-media-footer li {
  display: inline-block;
}
</style>