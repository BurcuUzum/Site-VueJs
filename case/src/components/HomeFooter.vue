<template>
  <div class="container FooterContainer">
    <div class="FooterRow">
      <div class="row">
        <div class="col-lg-2 col-md-6 col-sm-12 col-" style = "padding-left: 25px;">
          <ul>
            <li class="head">Kurumsal</li>
            <li>
              <ul class="submenus">
                <li>Hakkımızda</li>
                <li>Kampanyalar</li>
                <li>Banka Hesap Numaraları</li>
                <li>Blog</li>
                <li>Haberler</li>
              </ul>
            </li>
          </ul>
        </div>
        <div class="col-lg-2 col-md-6 col-sm-12 col-">
          <ul>
            <li class="head">Müşteri Hizmetleri</li>
            <li>
              <ul class="submenus">
                <li>Sipariş Sorgulama</li>
                <li>Teslimat ve Kargo</li>
                <li>İade ve Değişim</li>
                <li>Üyelik Sözleşmesi</li>
                <li>Gizlilik ve Güvenlik</li>
              </ul>
            </li>
          </ul>
        </div>
        <div class="col-lg-2 col-md-6 col-sm-12 col-">
          <ul>
            <li class="head">Yardım</li>
            <li>
              <ul class="submenus">
                <li>İletişim Bilgileri</li>
                <li>sıkça Sorulan sorular</li>
              </ul>
            </li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12 col-">
          <ul>
            <li class="head">İletişim</li>
            <li>
              <ul class="submenus">
                <li>
                  <strong>Adres: </strong>Şehit Polis Fethi Sekin Cad. No: 1/706
                  Martı Tower, Konak - İzmir
                </li>
                <li><strong>Telefon: </strong>0850555555</li>
              </ul>
            </li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12 col-">
          <ul>
            <li class="head">Bizi Takip Edin</li>
            <li>
              <ul class="submenus">
                <div class="social">
                  <li>
                    <ul>
                      <li><i class="bi bi-facebook"></i></li>
                      <li><i class="bi bi-twitter"></i></li>
                      <li><i class="bi bi-youtube"></i></li>
                      <li><i class="bi bi-instagram"></i></li>
                    </ul>
                  </li>
                </div>
                <li>E-Bültene üye olun, gelişmeleri kaçırmayın.</li>
                <li>
                  <div class="form-group">
                    <input type="email" placeholder="E-posta adresiniz" />
                    <div><button class="submit">→</button></div>
                  </div>
                </li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <hr />
    <div class="row copyright">
      <div class="col-6">
        <p>Copyright © 2022 Karma-Kırmızı</p>
      </div>
      <div class="col-6">
        <div class="logo">
          <img width="152" height="58" src="../img/logo.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">

$white: #fff;
$red: red;
$light-gray: #f9f6f6;

.FooterContainer {
  max-width: 1440px !important;
  background-color: $light-gray;
  .FooterRow {
    padding: 40px 20px;
  }
  ul {
    padding: 0;
  }
  .submenus {
    padding-top: 15px;
    .form-group {
      display: inline-flex;
    }
    .submit {
      border: none;
      background: $red;
      height: 35px;
      width: 35px;
      color: $white;
      font-size: 22px;
    }
    input {
      border: none;
    }
    .social {
      li {
        list-style-type: none;
        padding-bottom: 5px;
        display: inline-flex;
        padding-right: 15px;
      }
    }
  }
  li {
    list-style-type: none;
    padding-bottom: 5px;
  }
  li.head {
    font-weight: 700;
    font-size: 18px;
  }
  p {
    padding-top: 10px;
  }
  .logo img {
    float: right;
  }
  .copyright {
    padding: 0 20px;
  }

  @media screen and (max-width: 772px){
    text-align: center;
  }
}
</style>
