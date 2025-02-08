<script setup>

</script>

<template>
  <body>
    <div class="introContent">
      <div class="card">

        <div class="open-card">
          <img src="./images/intro-img.png" alt="intro" class="intro-img">
  
          <div class="text-card_color">
            <div class="text-card">
              <h1 class="header">Аренда спортивного инвентаря и снаряжения для <span class="color-change">активного отдыха</span></h1>
              <p class="open-card_desc">Пункт по прокату спортивного инвентаря в Перми «Шторм» — это широкий выбор экипировки и оборудования для занятия спортом на улице. </p>
            </div>
          </div>
        </div>

        <div class="advantages">
          <div class="cards">
            <div class="cards-content">
              <div class="card-icon">
                <img src="./images/favorable-conditions.png" alt="" class="icon-img-lil">
              </div>

              <div class="text">
                <h3 class="card-header">Выгодные условия</h3>
                <p>Прокат велосипедов, удобное расположение</p>
              </div>
            </div>
            
          </div>

          <div class="cards">
            <div class="cards-content">
              <div class="card-icon">
                <img src="./images/reasonable-prices.png" alt="" class="icon-img-lil">
              </div>
  
              <div class="text">
                <h3 class="card-header">Приемлемые цены</h3>
                <p>Прокат велосипедов, удобное расположение</p>
              </div>
            </div>
          </div>

          <div class="cards">
            <div class="cards-content">
              <div class="card-icon">
                <img src="./images/convenient-location.png" alt="" class="icon-img-lil">
              </div>
  
              <div class="text">
                <h3 class="card-header">Удобное местоположение</h3>
                <p>Прокат велосипедов, удобное расположение</p>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>

  </body>

</template>

<style>
h1, h2, h3, p{
  padding: 0 0;
  margin: 0 0;
  font-family: "Inter", serif;
}

.introContent{
  background: #F4F6F8 url("./images/vector.png") no-repeat center;
}

.card{
  width: 100%;
  max-width: 80.5rem;
  margin: 0 auto;
}

.intro-img{
  position: relative;
  border-radius: 1.25rem;
  z-index: 1;
  margin-top: 3.125rem;
}

.text-card{
  position: absolute;
  z-index: 3;
}

.text-card_color{
  position: absolute;
  z-index: 2;
  width: 100%;
  max-width: 46.25rem;
  height: 20.25rem;
  margin: 2rem 2rem;
  margin-top: -28%;
  margin-bottom: 20%;
  padding: 2rem 2.5rem 2rem 2.5rem;
  border-radius: 1.25rem;
  background-color: #fff;
}

.color-change{
  color: #5B7DDE;
}

.header{
  width: 100%;
  max-width: 43.75rem;
  font-size: 3.25rem;
  font-family: "Inter", serif;
}

.open-card_desc{
  width: 100%;
  max-width: 41.25rem;
  font-family: "Inter", serif;
  font-size: 1.125rem;
}

/*cards*/
.advantages{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 1rem;
}

.cards{
  width: 100%;
  max-width: 26.1875rem;
  background-color: #fff;
  display: flex;
  flex-direction: row;
  border-radius: 0.9375rem;
  margin-top: 1rem;
  margin-bottom: 5.5625rem;
}

.cards-content{
  width: 100%;
  max-width: 23.125rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 1.5rem 1.5rem;
}

.text{
  padding-left: 1rem;
}

.card-header{
  padding-bottom: 0.5rem;
}

.icon-img-lil{
  padding-bottom: 1.2rem;
}
</style>