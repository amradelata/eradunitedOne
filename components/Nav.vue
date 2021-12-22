<template>
  <nav>
    <div class="navOne">
      <ul class="social-media-nav">
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
          <a href="" class="hvr-grow-shadow"><i class="fab fa-vimeo-v"></i></a>
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
      <span>هاتف : <a href="tel:0114762606">0114762606</a></span>
      <span>فاكس : <a href="fax:0114762125">0114762125</a></span>
    </div>
    <div class="navTow">
      <b-container class="bv-example-row">
        <b-row class="text-center">
          <b-col cols="4"
            ><img class="header_logo" src="~/assets/img/header_logo.png" alt=""
          /></b-col>

          <b-col cols="6">
            <b-input-group>
              <b-input-group-prepend>
                <b-input-group-prepend>
                  <b-dropdown text="يرجى الاختيار">
                    <b-dropdown-item href="#">Action</b-dropdown-item>
                    <b-dropdown-item href="#">Another action</b-dropdown-item>
                    <b-dropdown-item href="#"
                      >Something else here</b-dropdown-item
                    >
                  </b-dropdown>
                </b-input-group-prepend>
              </b-input-group-prepend>

              <b-form-input type="text" min="0.00"></b-form-input>

              <b-button class="searchbtn">بحث</b-button>
            </b-input-group></b-col
          >
          <b-col cols="2">
            <div>
              <b-dropdown offset="25" text="حسابى" class="m-2">
                <b-dropdown-item href="#">Action</b-dropdown-item>
                <b-dropdown-item href="#">Another action</b-dropdown-item>
                <b-dropdown-item href="#">Something else here</b-dropdown-item>
              </b-dropdown>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </nav>
</template>
<style scoped>
nav {
  background-color: #fff;
}
.navOne {
  margin: 0 auto;
  text-align: center;
  padding: 10px 0;
}
.navOne span {
  color: #149045;
  margin: 0 5px;
}
ul li {
  font-size: 20px;
  border-left: 1px solid #d6ebde;
  padding: 0 15px;
  display: inline-block;
}
ul li a i,
.navOne a {
  color: #149045;
}
.social-media-nav {
  display: inline-block;
}
.searchbtn {
  background: #149045;
}
.text-center {
  align-items: center;
}
#dropdown-offset {
  background: transparent !important;
  color: #000;
}
</style>