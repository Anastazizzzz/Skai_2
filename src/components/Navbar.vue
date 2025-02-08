<script setup>

</script>

<template>
  <nav>
    <img src="./images/skai-logo.png" class="logo" alt="logo"/>
      
    <div class="link-list">
      <ul class="link-list_content">
        <li><button class="link-button"><a href="#">Прокат инвентаря</a></button></li>
        <li><button class="link-button"><a href="#">Каток</a></button></li>
        <li><button class="link-button"><a href="#">Кафе</a></button></li>
        <li><button class="link-button"><a href="#">Сервис</a></button></li>
        <li><button class="link-button"><a href="#">Прайс-лист</a></button></li>
        <li><button class="link-button"><a href="#">Контакты</a></button></li>
      </ul>
    </div>

    <div class="aders">
      <p class="work-schedule">
        Ежедневно 10.00-22.00
      </p>
    </div>

    <div class="phone-number">
      <button class="phone-number_button">
        <img src="./images/phone.png" class="phone-number_img"/>
      </button>
    </div>
  </nav>
</template>

<style scoped>
nav{
  width: 100%;
  max-width: 80.5rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  margin: 1.5rem auto;
}

.logo{
  width: 9.125rem;
  height: 3rem;
}

/*list*/
.link-list{
  width: 100%;
  max-width: 44.4rem;
}

.link-list_content{
  list-style-type: none;
  display: flex;
  flex-direction: row;
}

.link-button{
  padding: 0.75rem 1rem;
  border: none;
  border-radius: 3.625rem;
  margin-left: 0.625rem;
}

a{
  text-decoration: none;
  color: black;
}

/*work schedule*/
p{
  font-family: "Inter", serif;
}

.work-schedule{
  font-size: 0.81rem;
  color: rgba(91, 91, 91, 1);
}

/*phone buttom*/
.phone-number_button{
  width: 2.375rem;
  height: 2.375rem;
  padding:  0.71rem;
  background-color: rgba(244, 246, 248, 1);
  ;
  border: none;
  border-radius: 0.7rem;
}

.phone-number_img{
  width: 0.93rem;
}

/*1060*/
/*920*/
/*800*/
/*580*/
/*430*/
/*360*/
</style>
