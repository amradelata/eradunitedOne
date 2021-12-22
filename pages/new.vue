<template>
  <div>
    <div class="dad">
      <div class="card">
        <div class="overflow">
          <img class="logoFront" src="~/assets/img/card/logoFront.svg" alt="" />
          <p class="cardTitle">DISCOUNT CARD</p>
          <img class="circle" src="~/assets/img/card/circle.svg" alt="" />
          <img class="qr" src="~/assets/img/card/qr.svg" alt="" />

          <div class="CardContent">
            <p class="cardName">Name : AMR ADEL ATA</p>
            <div class="cardInformation">
              <p class="cardLapel">Card number</p>
              <p class="cardData">0000000</p>
            </div>
            <div class="cardInformation">
              <p class="cardLapel">Expirs</p>
              <p class="cardData">10/20</p>
            </div>
          </div>
          <div class="cardSocial">
            <span>DOWNLOUD OUR APP</span>
            <img src="~/assets/img/card/social.svg" alt="" />
            <h5>www.tamdiscount.com</h5>
          </div>
        </div>
      </div>
    </div>
    <div class="dad">
      <div class="card">
        <!-- <div class="overflow"> -->
        <img class="backLogo" src="~/assets/img/card/wightLogo.svg" alt="" />
        <p class="backP">
          نحن نتعاقد مع القطـاع الصحى والمستشفيـات والمراكز الطبية ومراكز طب
          الأسنان والجلدية والليزر ومراكز التجميل والتغذية العلاجية وطب العيون
          والعلاج الطبيعي والمختبرات والأشعة ومعـامـل التحـاليل والأشعــة
          وقطــاع التعليـم والمـدارس الخـاصــة والحضانات ومعارض النظارات الطبية
          والشمسية التـدريبة ومراكز الدورات التدريبية والكورسات وأماكن الترفية
          والمطاعم القطـاع السيـاحـى والــرحـــلات المـراكـز الـرياضية والنـوادى
          وخدمات السيارات
        </p>
        <div class="backSocial">
          <span>DOWNLOUD OUR APP</span>
          <img src="~/assets/img/card/social.svg" alt="" />
          <h4>www.tamdiscount.com</h4>
        </div>
        <img class="backQr" src="~/assets/img/card/backQr.svg" alt="" />
        <div class="wightBox"></div>
        <p class="tam">tam discount card</p>
        <!-- </div> -->
      </div>
    </div>
  </div>
</template>
<style scoped>
.dad {
  position: relative;
}
.card {
  color: #f6f6f6;
  /* background-color: #012d5a; */
  background-color: #012d5a;
  width: 90vw;
  height: 90vh;
  margin: 50px auto;
}
.logoFront {
  position: absolute;
  top: 10%;
  left: 10%;
  width: 190px;
  height: 97px;
}
.cardTitle {
  position: absolute;
  top: 10%;
  right: 10%;
  font-size: 35.85px;
}
.overflow {
  /* background: #012e5a78; */
  /* background-image: url("~/assets/img/card/BK.svg"); */
  background-position: center center;
  background-size: cover;

  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  /* transform: translate(-50%, -50%); */
  z-index: 9999999;
}
.circle {
  width: 500px;
  height: 600px;
  position: absolute;
  right: 0;
  overflow: hidden;
  opacity: 0.6;
}
.Bk {
  width: 100%;
}
.qr {
  position: absolute;
  right: 10%;
  top: 25%;
  width: 212px;
  height: 212px;
}
.CardContent {
  position: absolute;
  left: 10%;
  bottom: 10%;
}
.cardInformation {
  display: inline-block;
  margin-right: 50px;
}
.cardSocial {
  position: absolute;
  bottom: 10%;
  right: 10%;
}
.backSocial {
  position: absolute;
  bottom: 10%;
  right: 12%;
}
.backQr {
  position: absolute;
  bottom: 10%;
  right: 5%;
}
.cardName {
  font-size: 41px;
}
.cardLapel {
  font-size: 24px;
}
.cardData {
  font-size: 30px;
  font-weight: bold;
}

/* back */
.backLogo {
  width: 136px;
  height: 49px;
  position: absolute;
  top: 5%;
  left: 5%;
}
.backP {
  width: 415px;
  font-size: 13px;
  text-align: right;
  position: absolute;
  top: 5%;
  right: 5%;
}
.tam {
  position: absolute;
  bottom: 5%;
  left: 5%;
  font-size: 26px;
}
.wightBox {
  width: 90%;
  height: 128px;

  background: #f6f6f6;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
</style>