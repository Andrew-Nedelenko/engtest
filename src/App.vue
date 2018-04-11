<template>
  <div id="app">
    <nav class="nav_bar">
        <div class="container-fluid nav_bt_conteiner">
          <div class="row">
            <div class="col-sm-1 col-xs-1"></div>
            <div class="col-sm-2 col-xs-2">
              <h1>Site logo</h1>
            </div>
            <div class="col-sm-4 col-xs-4">
              <input type="text" name="search">
              <i class="fa fa-map-marker"></i>
              <i class="fa fa-sort-down"></i>
              <i class="fa fa-search"></i>
              
            </div>
            <div class="col-sm-3 col-xs-3"></div>
            <div class="col-sm-1 col-xs-1">
              
              <i class="fa fa-bell"></i>
            </div>
            <div class="col-sm-1 col-xs-1">
              <img src="src\components\img\noavatar.png" alt="avatar">
            </div>
          </div>
        </div>
      </nav>
    <header class="header">
      <img src="src\components\img\main_slide.gif" alt="logo">   
    </header>
    <main class="main">
      <div class="container">
        <div class="row">
          <div class="col-sm-8 col-xs-8">
            <div class="leftConteiner">
              <i class="fa fa-leaf"></i>
              <h1>Английский для детей</h1>
              <p>Лучше раньше чем никогда</p>
            </div>
          </div>
          <div class="col-sm-4 col-xs-4">
            <div class="rightConteiner">
              <h1>Курсы</h1>
              <span>Английский язык</span>
            </div>
          </div>
        </div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-sm-8 col-xs-8">
            <div class="leftTable">
              <i class="fa fa-graduation-cap"></i>
              <h1 >В каком возрасте начать обучение?</h1>
              <i class="fa fa-chevron-up" @click="rotate = !rotate, show = !show" v-bind:class="{ rotate: rotate }"></i>
              <transition name='fade'>
              <aside v-if="show">До пяти лет дети обладают лингвистической гениальностью. Они способны запоминать 20-30 новых слов в день. 
              Простая арифметика дает впечатляющий результат – 7-10 тысяч слов в год. Да мы и в родном русском столько не используем,
               а что говорить об иностранном. Способности к языкам, безусловно, либо есть, либо нет.</aside>
              </transition>
            </div>
            <div class="leftTable">
              <i class="fa fa-graduation-cap"></i>
              <h1>В каком возрасте начать обучение?</h1>
              <i class="fa fa-chevron-up" @click="rotate2 = !rotate2, showNext = !showNext" v-bind:class="{ rotate2: rotate2 }"></i>
              <transition name='fade'>
              <aside v-if="showNext">До пяти лет дети обладают лингвистической гениальностью. Они способны запоминать 20-30 новых слов в день. 
              Простая арифметика дает впечатляющий результат – 7-10 тысяч слов в год. Да мы и в родном русском столько не используем,
               а что говорить об иностранном. Способности к языкам, безусловно, либо есть, либо нет.</aside>
              </transition>
            </div>
          </div>
          <div class="col-sm-4 col-xs-4">
            <div class="rightTable">
              <img src="src\components\img\logo.gif" alt="logo" class="img-thumbnail">
              <i class="fa fa-star"></i>
              <img class="imgClass" src="src\components\img\class.gif" alt="">
              <i class="fa fa-check-square"></i>
              <h1>Школа <br>«Let Speak»</h1>
              <p>Репетиторы носители языка главное наше преимущес...</p>
              <i class="fa fa-map-marker"></i>
              <h2>Украина Киев</h2>
            </div>
          </div>
        </div>
      </div>
    </main>
    <div class="container">
      <div class="row">
        <div class="col-sm-8 col-md-8">
          <h1 class="h1">Курсы Английского в Киеве</h1>
        </div>
        <div class="col-sm-4 col-md-8"></div>
      </div>
    </div>
      <section>
        <div class="container">
      <div class="row slide_container">
        <div class="col-sm-3 col-xs-3">
          <div class="rightTable">
              <img src="src\components\img\logo.gif" alt="logo">
              <i class="fa fa-star"></i>
              <img class="imgClass" src="src\components\img\class.gif" alt="">
              <i class="fa fa-check-square"></i>
              <h1>Школа <br>«Let Speak»</h1>
              <p>Репетиторы носители языка главное наше преимущес...</p>
              <i class="fa fa-map-marker"></i>
              <h2>Украина Киев</h2>
            </div>
        </div>
        <div class="col-sm-3 col-xs-3">
          <div class="rightTable">
              <img src="src\components\img\logo.gif" alt="logo">
              <i class="fa fa-star"></i>
              <img class="imgClass" src="src\components\img\class.gif" alt="">
              <i class="fa fa-check-square"></i>
              <h1>Школа <br>«Let Speak»</h1>
              <p>Репетиторы носители языка главное наше преимущес...</p>
              <i class="fa fa-map-marker"></i>
              <h2>Украина Киев</h2>
            </div>
        </div>
        <div class="col-sm-3 col-xs-3">
          <div class="rightTable">
              <img src="src\components\img\logo.gif" alt="logo">
              <i class="fa fa-star"></i>
              <img class="imgClass" src="src\components\img\class.gif" alt="">
              <i class="fa fa-check-square"></i>
              <h1>Школа <br>«Let Speak»</h1>
              <p>Репетиторы носители языка главное наше преимущес...</p>
              <i class="fa fa-map-marker"></i>
              <h2>Украина Киев</h2>
            </div>
        </div>
        <div class="col-sm-3 col-xs-3">
          <div class="rightTable">
              <img src="src\components\img\logo.gif" alt="logo">
              <i class="fa fa-star"></i>
              <img class="imgClass" src="src\components\img\class.gif" alt="">
              <i class="fa fa-check-square"></i>
              <h1>Школа <br>«Let Speak»</h1>
              <p>Репетиторы носители языка главное наше преимущес...</p>
              <i class="fa fa-map-marker"></i>
              <h2>Украина Киев</h2>
            </div>
        </div>
      </div>
    </div>
      </section>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      show: true,
      showNext: false,
      rotate: false,
      rotate2: true
    }
    components: {
      Carousel,
      Slider
    }
  }
}
</script>

<style lang="scss" src=".\components\scss\main.scss">

</style>
