<template>
  <div>
    <ul>
      <li><nuxt-link to="/" class="link">الرئيسيه</nuxt-link></li>
      <li><nuxt-link to="/" class="link">الفروع</nuxt-link></li>
      <li><nuxt-link to="/" class="link">مكتب النشر</nuxt-link></li>
      <li><nuxt-link to="/" class="link">القسام</nuxt-link></li>
      <li><nuxt-link to="/" class="link">المدونة</nuxt-link></li>
      <li><nuxt-link to="/" class="link">اتصل بنا</nuxt-link></li>
      <li><b-button class="navBtn">صوروارسل</b-button></li>
    </ul>
  </div>
</template>

<style scoped>
ul {
  background-color: #149045;
  border-radius: 10px;
  width: 100%;
}
ul li {
  /* list-style: none;
  display: inline-block;
  margin: 0 5px; */

  display: inline-block;
  padding: 15px 20px;
}
ul li a {
  color: #fff;
  text-decoration: none;
}
.navBtn {
  background: #fff;
  color: #149045;
}
</style>