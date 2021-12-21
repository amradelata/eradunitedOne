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
            <li><input type="text" /></li></ul
        ></b-col>
        <b-col>
          <ul>
            <li>من نحن</li>
            <li>الشحن والتوصيل</li>
            <li>طرق الدفع</li>
            <li>شروط الاستخدام</li>
            <li>سياسه الخصوصية</li>
          </ul>
        </b-col>
        <b-col>
          <div class="row">
            <div class="col">
              <ul>
                <li>الرئيسيه</li>
                <li>الفروع</li>
                <li>مكتب النشر</li>
                <li>القسام</li>
                <li>اتصل بنا</li>
              </ul>
            </div>
            <div class="col">
              <nuxt-link to="/">
                <figure class="figure">
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
  </footer>
</template>
<style scoped>
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
</style>