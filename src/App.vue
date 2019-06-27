<template>
  <div id="app">
    <div class="wrapper container-fluid">
      <nav>
      <div class="navbar navbar-light nvb">
        <div class="mr-auto menu">
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
        <div class="icons">
        <a class="btn" href="/">
          <i class="fab fa-facebook-f"></i>        
        </a>
        <a class="btn" href="/">
          <i class="fab fa-instagram"></i>        
        </a>
        <a class="btn" href="/">
          <i class="fab fa-telegram-plane"></i>        
        </a>
      </div>
        <button class="btn submit">Войти</button>
      </div>
    </nav>

    <section class="body1">
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
      <div class="body2 row">
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
      <!-- BODY3 -->
      <div class="body3 row align-items-center">
        <div class="col-3">
          <img src="./assets/left-stool.png" alt="">
        </div>
        <div class="container col-6">
          <img src="./assets/shape.png" class="mx-auto d-block" alt="">
          <h1>Основные преимущества нашего <br> Коворкинг-центра</h1>
          <div class="row content col-12">
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
        <div class="col">
            <img src="./assets/right-stool.png" alt="">
        </div>
      </div>
      <!-- BODY4 -->
      <div class="body4">
        <h1><span>iWORK</span>— поможет Вам <br>
найти нужных людей</h1>
      </div>
      <!-- BODY5 -->
      <div class="body5">
        <img src="@/assets/shape.png" alt="">
        <div class="body5-title">
          <h2>Тарифные планы</h2>
        </div>
        <div class="row">
          <div class="col-3"></div>
          <!-- Cards row -->
          <div class="col row">
            <!-- 1-card  -->
            <div class="col cards">
              <div class="card-title">
                <h3>Гибкий график</h3>
              </div>
              <div class="card-price">
               <h5>120 000 сум / месяц</h5>
              </div>
              <div class="card-body">
                <p>1 день / мес включено</p>
                <p>1 ч / мес Конференц-залы</p>
                <p>Высокоскоростной интернет</p>
                <p>Доступ к профессиональной сети</p>
                <p>Кухня, бесплатный кофе</p>
                <p>—</p>
                <p>—</p>
                <p>—</p>
              </div>
              <div>
                <a class="btn-main" href="/">Купить</a>
              </div>
            </div>
            <!-- 2-card -->
            <div class="col cards">
              <div class="card-title">
                <h3>Неполная занятость</h3>
              </div>
              <div class="card-price">
               <h5>500 000 сум / месяц</h5>
              </div>
              <div class="card-body">
                <p>3 день / мес включено</p>
                <p>2 ч / мес конференц-залы</p>
                <p>Высокоскоростной интернет</p>
                <p>Доступ к профессиональной сети</p>
                <p>Кухня, бесплатный кофе</p>
                <p>Семинары / Лекции</p>
                <p>Менеджеры сообщества</p>
                <p>—</p>
              </div>
              <div>
                <a class="btn-main" href="/">Купить</a>
              </div>
            </div>
            <!-- 3-card -->
            <div class="col cards">
              <div class="card-title">
                <h3>Гибкий график</h3>
              </div>
              <div class="card-price">
               <h5>120 000 сум / месяц</h5>
              </div>
              <div class="card-body">
                <p>Неограниченное количество рабочих часов</p>
                <p>Неограниченное количество конференц-залов</p>
                <p>Высокоскоростной интернет</p>
                <p>Доступ к профессиональной сети</p>
                <p>Кухня, бесплатный кофе</p>
                <p>Семинары / Лекции</p>
                <p>Прием гостей</p>
              </div>
              <div>
                <a class="btn-main" href="/">Купить</a>
              </div>
            </div>
          </div>
          <div class="col-3"></div>
        </div>
      </div>
      <div class="body-map">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2997.1745739777757!2d69.26251651572525!3d41.30506570905678!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38ae8b201748770b%3A0x1d6fab843c00d089!2sAstronaut+Dzhanibekov+Monument%2C+Afrosiab+Street%2C+Tashkent%2C+Uzbekistan!5e0!3m2!1sen!2s!4v1561639918779!5m2!1sen!2s" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
      </div>

    </section>


    <footer>
      <img src="@/assets/logotip.png" alt="" class="mx-auto d-block">
      <div class="icons">
        <a class="btn" href="/">
          <i class="fab fa-facebook-f"></i>        
        </a>
        <a class="btn" href="/">
          <i class="fab fa-instagram"></i>        
        </a>
        <a class="btn" href="/">
          <i class="fab fa-telegram-plane"></i>        
        </a>
      </div>
      <div class="author">
        <p>©2016 iWork.uz. Все права защищены
          <br>
          Разработка сайта: <span>Online Service Group</span>
        </p>
      </div>
      
    </footer>
    </div>
    
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
  width: 100%;
}
.nvb {
  margin: auto;
  width: 100%;
  background-color: white;
  * {
    text-decoration: none;
    color: black;
    font-size: 16px;
  }
  a:hover {
    text-decoration: none;
  }
  .menu, .icons, button, .menu * {
    margin-right: 10px;
    margin-left: 10px;
    padding-right: 10px;
  }
  .icons i {
    color: white;
  }
  .submit {
    border-radius: 999px;
    border: 2px solid $button_green;
    color: $button_green;
    width: 120px;
  }
  .submit:hover {
    color: white;
    background-color: $button_green;
    border-color: white;
  }
}
.icons {
  padding: 15px;
  .btn {
    border-radius: 50%;
    background-color: $main-clr;
    margin: 10px;
    width: 50px;
    height: 50px;
    overflow: hidden;
    i {
      line-height: 35px;
      font-size: 20px;
      transition: 0.2s linear;
    }
  }
  .btn:hover {
    background-color: white;
    i {
      transform: scale(1.3);
      color: $main-clr;
    }
  }
}

.body1 {
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
      font-size: 25px;
      padding-right: 30px;
      padding-left: 30px;
    }
    .btn:hover {
      color: black;
    }
  }
  .body2 {
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
  .body3 {
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
.body4 {
  background-image: url("./assets/layer.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
    padding: 120px;
  * {
    color: white;
    text-align: center;
    text-transform: uppercase;
    margin-bottom: 0;
  }
  span {
    color:$main-clr;
    text-transform: none;
  }
}
.body5 {
  padding-top: 30px;
  text-align: center;
  padding-bottom: 30px;
  .body5-title {
    padding-top: 20px;
    padding-bottom: 20px;
  }
  .col .col {
    padding: 0px;
    margin: 10px;
    border: 1px solid;
    margin-bottom: 20px;
    padding-bottom: 20px;
    border: 1px solid #e4e4e4;
    border-radius: 9px;
    box-shadow: 0 5px 0 rgba(0, 0, 0, 0.2);
  }
  .card-title {
    border-top-right-radius: 9px;
    border-top-left-radius: 9px;
    background-image: url("./assets/var1.png");
    background-repeat: no-repeat;
    background-size: cover;
    color: $main-clr;
    height: 80px;
    margin: 0;
    text-align: center;
    padding-top: 15px;
  }
  .card-price {
    background-color: $button_green;
    padding-top: 12px;
    height: 50px;
    margin: 0;
    color: white;
  }
  .card-body {
    height: 350px;
  }
}
.btn-main {
  border-radius: 28px;
  background-color: $button_green;
  padding: 5px;
  padding-right: 40px;
  padding-left: 40px;
  text-decoration: none;
  color: white;
  text-align: center;
  box-shadow: 0 2px 0 #272727;
  text-transform: uppercase;
  font-weight: 700;
}
.btn-main:hover {
  color:$button_green;
  background-color: white;
  text-decoration: none;
}
.body-map {
  iframe {
    width: 100%;
    height: 500px;
  }
}
footer {
  background-image: url("./assets/footer-fone.svg");
  height: 350px;
  text-align: center;
  padding-top: 30px;
    margin-bottom: 0;
  * {
    text-align: center;
    color: white;
  }
  .author {
    p {
      margin-bottom: 0px;
      span {
        color: $main-clr;
      }
    }
  }
}
</style>