<template>
  <div id="app">
    <nav>
      <div class="navbar navbar-light nvb">
        <div class="mr-auto">
          <router-link to="/"><img src="@/assets/logo1.png" alt=""></router-link>
          <router-link to="/">Услуги и цены</router-link>
          <router-link to="/">Акции и скидки</router-link>
          <router-link to="/">Резиденты</router-link>
          <router-link to="/">Календарь</router-link>
          <router-link to="/">Галерея</router-link>
          <router-link to="/">Новости</router-link>
          <router-link to="/">Бронь</router-link>
          <router-link to="/">Контакты</router-link>
        </div>
        <a class="btn-floating btn-lg btn-fb bg-border" href="/"><i class="fa fa-facebook-f"></i></a>
        <!--Twitter-->
        <a class="btn-floating btn-lg btn-in bg-border" href="/"><i class="fa fa-instagram"></i></a>
        <!--Google +-->
        <a class="btn-floating btn-lg btn-tg bg-border" href="/"><i class="fa fa-telegram"></i></a>
        <button class="btn">Войти</button>
      </div>
    </nav>

    <section class="body-main">
      <div class="body-reserve">
        <img src="@/assets/logotip2.png" class="mx-auto d-block" alt="">
        <img src="@/assets/Coworking.png" class="mx-auto d-block" alt="">
        <p>
          Общее пространство для работы и развития бизнеса <br>
Для бизнесменов, фрилансеров и стартап – проектов. <br>
Аренда рабочих мест, офисов, переговорных комнат, конференц - залов.
        </p>
        <div class="reserve">
          <a class="btn" href="/">Забронировать</a>
        </div>
      </div>
      <!-- BODY2 -->
      <div class="body-about row">
        <div class="col-7">
          <div id="demo" class="carousel slide" data-ride="carousel">

            <!-- Indicators -->
            <ul class="carousel-indicators">
              <li data-target="#demo" data-slide-to="0" class="active"></li>
              <li data-target="#demo" data-slide-to="1"></li>
              <li data-target="#demo" data-slide-to="2"></li>
            </ul>

            <!-- The slideshow -->
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="./assets/foto.png" alt="Los Angeles">
              </div>
              <div class="carousel-item">
                <img src="./assets/foto.png" alt="Chicago">
              </div>
              <div class="carousel-item">
                <img src="./assets/foto.png" alt="New York">
              </div>
            </div>

            <!-- Left and right controls -->
            <a class="carousel-control-prev" href="#demo" data-slide="prev">
              <span class="carousel-control-prev-icon"></span>
            </a>
            <a class="carousel-control-next" href="#demo" data-slide="next">
              <span class="carousel-control-next-icon"></span>
            </a>
          </div>
        </div>
        <div class="col-5">
          <div class="body2-img">
            <img src="./assets/logo2.png" alt="" class="mx-auto d-block">
          </div>
          <div class="body2-text">
          <h2>Немного о нас и о нашей цели</h2>
          <p>
            Независимо от того, Вы работаете для себя или же удаленно, это здорово, это независимость. Наша цель состоит в том, чтобы создать среду, которая позволяет Вам сосредоточиться на том, что действительно важно, качественно сделать свою работу и познакомиться с интересными людьми.
Все это в одном месте!
          </p>            
          </div>
          <div class="resident">
          <a class="btn" href="/">стать резидентом</a>
        </div>
        </div>
      </div>
      <!-- BODY4 -->
      <div class="body-coworking-center row align-items-center">
        <div>
          <img src="./assets/left-stool.png" alt="">
        </div>
        <div class="container">
          <img src="./assets/shape.png" class="mx-auto d-block" alt="">
          <h1>Основные преимущества нашего <br> Коворкинг-центра</h1>
          <div class="row content">
            <div class="div1 row">
              <div class="col-4">
                <img src="./assets/item1.png" alt="">
                <p>Быстрый, беспроводной интернет <br> нового поколения без лимитов и <br> ограничения трафика</p>
              </div>
              <div class="col-4">
                <img src="./assets/item2.png" alt="">
                <p>Ежедневное обучение происходит за счет знакомства с новыми людьми</p>
              </div>
              <div class="col-4">
                <img src="./assets/item3.png" alt="">
                <p>Возможность продвигать и рекламировать свои услуги потенциальным заказчикам</p>
              </div>
              
            </div>
            <div class="div2 row">
              <div class="col-4">
                <img src="./assets/item4.png" alt="">
                <p>Место для встречи с клиентами, руководителями и специалистами</p>
              </div>
              <div class="col-4">
                <img src="./assets/item5.png" alt="">
                <p>Возможность проведения различных презентаций, мастер-классов и  хакатонов</p>
              </div>
              <div class="col-4">
                <img src="./assets/item6.png" alt="">
                <p>Использование техники и технологий (специализированный софт, <br> оборудование, 3Д-принтеры)</p>
              </div>
            </div>
          </div>
        </div>
        <div>
            <img src="./assets/right-stool.png" alt="">
        </div>
      </div>
      <div class="body-iwork">

      </div>
      <div class="body-tarif-plan">

      </div>
      <div class="body-map">

      </div>

    </section>


    <footer>
      <img src="@/assets/logotip.png" alt="" class="mx-auto d-block">
      <div class="icons">
        <a class="btn-floating btn-lg btn-fb bg-border" href="/"><i class="fa fa-facebook-f"></i></a>
        <!--Twitter-->
        <a class="btn-floating btn-lg btn-in bg-border" href="/"><i class="fa fa-instagram"></i></a>
        <!--Google +-->
        <a class="btn-floating btn-lg btn-tg bg-border" href="/"><i class="fa fa-telegram"></i></a>
      </div>
      <div class="author">
        <p>©2016 iWork.uz. Все права защищены
          <br>
          Разработка сайта: <span>Online Service Group</span>
        </p>
      </div>
      
    </footer>
  </div>
</template>

<script>
export default {
  
}
</script>


<style lang="scss">
$button_green: #2ebd7f;
$main-clr: #eab612;

#app {
  max-width: 1920px;
  margin: auto;
}
.nvb {
  margin: auto;
  max-width: 1721px;
  background-color: white;
  * {
    text-decoration: none;
    color: black;
    font-size: 16px;
    margin-right: 10px;
    margin-left: 10px;
    padding-right: 10px;
  }
  a:hover {
    text-decoration: none;
  }
  .btn-lg {
    border-radius: 50%;
    border: 2px solid;
    text-align: center;
    position: relative;
    font-size: 21px;
    * {
      color: white;
    }
  }
  .bg-border {
    width: 36px;
    height: 36px;
    padding: 0;
    color: white;
    background-color: $main-clr;
    line-height: 1.3;
  }
  .btn {
    border-radius: 999px;
    border: 2px solid $button_green;
    color: $button_green;
    width: 120px;
  }
  .btn:hover {
    color: white;
    background-color: $button_green;
    border-color: white;
  }
}
.icons {
  padding: 15px;
  a {
    border: 1px solid $main-clr;
    border-radius: 50%;
    background-color: $main-clr !important;
    font-size: 15px;
    margin-right: 10px;
    margin-left: auto;
  }
}

.body-main {
  .body-reserve {
    padding: 30px;
    background-image: url("./assets/body1-bg.png");
    background-color: $main-clr;
    background-repeat: no-repeat;
    margin: auto;
    display: block;
    p{
      text-align: center;
      margin-top: 30px;
      font: {
        size: 28px;
        weight:400;
        family: "Open Sans"
      }
      color: white;
    }
    .reserve {
      text-align: center;
      margin-top: 40px;
      margin-bottom: 200px;
    }
    .btn {
      border: 1px solid $button_green;
      border-radius: 28px;
      text-align: center;
      box-shadow: 0 3px 0 #272727;
      background-color: $button_green;
      color: white;
      text-transform: uppercase;
      font-weight: 700;
    }
    .btn:hover {
      color: black;
    }
  }
  .body-about {
    text-align: center;
    .body2-img {
      margin-top: 150px;
    }
    .body2-text {
      margin-top: 30px;
      p {
        margin-top: 20px;
        width: 600px;
        margin-left: auto;
        margin-right: auto;
      }
    }
    .btn {
      margin-top: 30px;
      border: 1px solid $button_green;
      border-radius: 28px;
      text-transform: uppercase;
      color: $button_green;
      font-weight: 700;
    }
    .btn:hover {
      color: white;
      background-color: $button_green;
    }
  }
  .body-coworking-center {
    margin-top: 60px;
    text-align: center;
    h1 {
      margin-top: 20px;
    }
  }
  .content {
    margin-top: 50px;
    .div1 {
      margin-top: 30px;
      img {
        margin-bottom: 30px;
      }
    }
    .div2 {
      margin-top: 30px;
      margin-bottom: 50px;
      img {
        margin-bottom: 30px;
      }
    }
  }
}
footer {
  background-image: url("./assets/footer-fone.svg");
  height: 350px;
  text-align: center;
  padding-top: 30px;
  * {
    text-align: center;
    color: white;
  }
  .author {
    p {
      span {
        color: $main-clr;
      }
    }
  }
}
</style>