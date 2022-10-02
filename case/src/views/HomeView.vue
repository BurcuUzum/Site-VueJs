<template>
  <div class="globalWrapper">
    <header>
      <div class="container helpContainer">
        <div class="row">
          <div class="col-lg-3 col-md-6 col-sm-6 col-">
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
          </div>
          <div class="col-6"></div>
          <div class="col-2">
            <div class="help">Yardım</div>
          </div>
          <div class="col">
            <div class="blog">Blog</div>
          </div>
        </div>
      </div>

      <div class="container searchContainer">
        <div class="row">
          <div class="col-lg-8 col-md-12 col-sm-12 col-">
            <div class="row">
              <div class="col-lg-4 col-md-12 col-sm-12 col- text-center">
                <img src="../img/headerlogo.jpg" />
              </div>
              <div class="col-lg-8 col-md-12 col-sm-12 col-">
                <div class="form-group">
                  <input type="email" placeholder="Ne aramıştınız... " />
                  <div><button class="submit">→</button></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-12 col-sm-12 col-">
            <div class="row">
              <div class="col-6">
                <div class="login">
                  <div class="icon">
                    <i class="bi bi-person-fill"></i>
                  </div>
                  <div class="content">
                    <div class="item">
                      <p>Giriş Yap<span>veya üye ol</span></p>
                    </div>
                    <div class="item">
                      <i class="bi bi-caret-down"></i>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="basket">
                  <div class="icon">
                    <i class="bi bi-cart-fill"></i>
                  </div>
                  <div class="content">
                    <div class="item">
                      <p>Sepet<span>0.00TL</span></p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="nav-menu">
        <i class="bi bi-list" @click="showMenu()"> </i>
        <div
          class="nav-content"
          :class="this.showMobileMenu ? 'open-menu' : 'closed-menu'"
        >
        <div class="close" @click="showMenu()"><i class="bi bi-x"></i></div>
          <ul class="nav-items">
            <li>Beyaz Eşya</li>
            <li>Ayakkabı</li>
            <li>Televizyonlar & Ses Sistemleri</li>
            <li>Ev Eşyaları</li>
            <li>kişisel bakım</li>
            <li>Mutfak Gereçleri</li>
          </ul>
        </div>
      </div>
    </header>
    <content>
      <div class="container homePage">
        <div class="row">
          <div class="col-12">
            <ul>
              <li><a class="item1" href="#">AnaSayfa</a></li>
              <li><a class="item2" href="#"> > </a></li>
              <li><a class="item3" href="#">Beyaz Eşya</a></li>
            </ul>
          </div>
        </div>
      </div>

      <div class="container categoryContainer">
        <div class="row">
          <div class="col-12">
            <p>
              <strong>Beyaz Eşya</strong> Eşya kategorisi içiriğindeki ürünler
              listeleniyor
            </p>
          </div>
        </div>
      </div>

      <div class="container listingContainer">
        <div class="row">
          <div class="col-lg-3 col-md-6 col-sm-12 col-">
            <form action="#">
              <select name="arrangement" class="list">
                <option value="">En son eklenenlere göre</option>
                <option value="">Fiyatı artan</option>
                <option value="">Fiyatı azalan</option>
              </select>
            </form>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 col-">
            <form action="#">
              <select name="arrangement" class="list">
                <option value="">Tüm ürünler</option>
                <option value="">İndirimdekiler</option>
              </select>
            </form>
          </div>
          <div class="col-6"></div>
        </div>
      </div>

      <div class="container productsContainer">
        <div class="row">
          <div class="col-lg-3 col-md-6 col-sm-12 col-">
            <div class="content">
              <div class="image">
                <img width="140" height="220" src="../img/product1.jpg" />
              </div>
              <p class="item1">Arçelik Bulaşık Makinesi</p>
              <p class="item2">6.200,90TL</p>
              <p class="item3"><strong>Taksitli Fiyat: </strong>3*3.100.10TL</p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 col-">
            <div class="content">
              <div class="image">
                <img width="140" height="220" src="../img/product1.jpg" />
              </div>
              <p class="item1">Arçelik Bulaşık Makinesi</p>
              <p class="item2">4.300,90TL</p>
              <p class="item3"><strong>Taksitli Fiyat: </strong>2*1.100.10TL</p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 col-">
            <div class="content">
              <div class="image">
                <img width="140" height="220" src="../img/product1.jpg" />
              </div>
              <p class="item1">Arçelik Bulaşık Makinesi</p>
              <p class="item2">5.700,90TL</p>
              <p class="item3"><strong>Taksitli Fiyat: </strong>2*3.100.10TL</p>
            </div>
          </div>
          <div class="col-lg-3 col-md-6 col-sm-12 col-">
            <div class="content">
              <div class="image">
                <img width="140" height="210" src="../img/product1.jpg" />
              </div>
              <p class="item1">Arçelik Bulaşık Makinesi</p>
              <p class="item2">6.900,30TL</p>
              <p class="item3"><strong>Taksitli Fiyat: </strong>3*3.200.10TL</p>
            </div>
          </div>
        </div>
      </div>
    </content>
    <HomeFooter />
  </div>
</template>
<script>
// @ is an alias to /src
import HomeFooter from "../components/HomeFooter.vue";
import axios from "axios";

export default {
  name: "HomeView",
  created() {
    console.log(localStorage.getItem("token"));
    if (localStorage.getItem("token") === null) {
      console.log("if girdi");
      this.login();
    } else {
      this.getProduct(localStorage.getItem("token"));
    }
  },
  data() {
    return {
      showMobileMenu: false,
    };
  },
  components: {
    HomeFooter,
  },
  methods: {
    login() {
      const params = { userName: "user", password: "123456" };
      const headers = {
        GUID: "0739-E657-C4F4-98B4",
        "access-control-allow-origin": "*",
      };
      axios
        .post("https://api.akilliticaretim.com/api/Auth/Login", params, {
          headers,
        })
        .then(function (response) {
          localStorage.setItem("token", response.data.data.token);
        });
    },
    getProduct(token) {
      console.log(token);
      console.log("getproduct çalıştı");

      axios
        .get("https://api.akilliticaretim.com/api/Product/ListProducts/0", {
          headers: { Authorization: `Bearer ${token}` },
        })
        .then((response) => {
          console.log(response);
        })
        .catch((error) => {
          console.log(error);
          console.log("gethata");
        });
    },
    showMenu() {
      this.showMobileMenu = !this.showMobileMenu;
    },
  },
};
</script>

<style lang="scss">

$white: #fff;
$red: red;
$light-gray: #f9f6f6;
$gray :gray;

header {
  .helpContainer {
    background-color: $light-gray;
    max-width: 1440px !important;
    .blog {
      text-align: center;
      padding-top: 10px;
      width: 50px;
      height: 44px;
      background: $red;
      color: $white;
      font-weight: 700;
    }
    .help{
      padding-top: 10px;
      float: right;
    }

    .social {
      padding-top: 10px;
      li {
        list-style-type: none;
        padding-bottom: 5px;
        display: inline-flex;
        padding-right: 15px;
      }
    }
  }

  .searchContainer {
    padding: 15px 0;
    img{
      @media (min-width: 768px){
        padding-bottom: 15px;
      }
      @media (min-width: 476px){
        padding-bottom: 15px;
      }
    }
    .login {
      cursor: pointer;
      .icon {
        float: left;
        margin: 5px 5px 5px 0;
        i {
          font-size: 18px;
        }
      }
      .content {
        float: left;
        display: flex;
        .item {
          i {
            margin: 5px 3px 3px 9px;
            display: block;
          }
          p {
            margin: 0;
            line-height: 17px;
            font-size: 14px;
            font-weight: bold;

            span {
              display: block;
              color: $gray;
              font-size: 12px;
            }
          }
        }
      }
    }

    .basket {
      cursor: pointer;
      .icon {
        float: left;
        margin: 5px 5px 5px 0;
        i {
          font-size: 18px;
        }
      }
      .content {
        float: left;
        display: flex;
        .item {
          i {
            margin: 5px 3px 3px 9px;
            display: block;
          }
          p {
            margin: 0;
            line-height: 17px;
            font-size: 12px;
            font-weight: bold;

            span {
              display: block;
              font-size: 12px;
            }
          }
        }
      }
    }
    .form-group {
      display: inline-flex;
      width: 100%;
      @media (min-width: 768px){
          padding-bottom: 15px;
        }
        @media (min-width: 476px){
        padding-bottom: 15px;
      }
      input {
        width: 100%;
        background: $light-gray;
        border: 1px solid gainsboro;
        font-size: 12px;
        padding-left: 20px;
        color: $gray;
       
      }
    }
    .submit {
      border: none;
      background: $red;
      height: 45px;
      width: 40px;
      color: $white;
      font-size: 22px;
    }

  }

  .nav-menu {
    background-color: $red;
    max-width: 1440px !important; 
    i {
      display:none;
    }
  }
  .nav-content {
    display: flex;
    justify-content: space-between;
    padding: 10px 30px;
    .close {
      color: $white;
    position: absolute;
    right: 10px;
    font-size: 35px;
    top: 0;
    }
  }
  .bi-list {
    color: $white;
    font-size: 22px;
  }
  .nav-items {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
    li {
      padding: 0 10px;
      color: $white;
    }
  }

  @media screen and (max-width: 768px) {
    .nav-menu {
      padding-top: 10px;
      position: absolute;
      width: 100%;
    }
    .open-menu {
      opacity: 1;
    position: fixed !important;
    top: 0;
    left: 0;
    z-index: 100 !important;
    width: 100%;
    height: 100%;
    background: $red;
    }
    .closed-menu {
      opacity: 0;
      height: 0;
      padding: 0;
    }
    .nav-content {
      flex-direction: column;
      z-index: 100;
      position: relative;
      transition: all 0.2s ease-out;
      padding-left: 15px;
    }
    .nav-items {
      flex-direction: column;
      li{
        padding-left:0;
      }
    }
    .nav-menu{
      i {
      display: block;
      text-align: right;
      padding: 0 10px 10px 0;
    }
    }
    
  }
}

.homePage {
  background-color: $light-gray;
  max-width: 1440px !important;
  padding-top: 10px;
  ul {
    display: flex;
    list-style-type: none;
    color: $gray;
  }
  .item1,
  .item2 {
    color: $gray;
  }
  .item3 {
    color: #333;
  }
  ul a {
    text-decoration: none;
    margin: 0 5px;
    font-weight: 700;
  }
}

.categoryContainer {
  margin: 30px 0px 10px 0;
  strong {
    font-size: 18px;
  }
  p {
    text-align: center;
  }
}

.listingContainer {
  form{
    @media (max-width: 768px){
      padding-bottom: 20px;
    }
  }
  .list {
    padding: 5px 10px;
    width: 100%;
    height: 45px;
  }
  select {
    color: $gray;
    font-size: 14px;
    height: 40px;
  }
}

.productsContainer {
  margin: 20px 0 20px 0;
  .col-sm-12{
    @media (min-width: 576px){
      padding-bottom: 20px;
    }
  }
   
  .content {
    border: 3px solid $light-gray;
  }
  .image {
    text-align: center;
    margin: 20px;
  }
  p {
    text-align: center;
  }
  .item2{
    font-weight: 700;
  }
}
</style>
