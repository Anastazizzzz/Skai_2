<script>


</script>

<template>
    <div class="content_block">
        <div class="content_services">
            <div class="header_services">
    
                <h2 class="header_grid">
                    Дополнительные услуги
                </h2>
                <p>
                    На все случаи жизни
                </p>
    
            </div>
    
            <div class="grid_services">
                <div class="card_grid">
    
                    <div class="grid_img-card">
                        <div class="grid_img">
                            <img src="./images/master.png" alt="#" class="card-img">
                        </div>
                        <div class="txt_img">
                            <h3>Ski-сервис</h3>
                            <p>У нас есть всё, что необходимо для подготовки и обслуживания инвентаря.</p>
                        </div>
                    </div>
    
                    <div class="grid_img-card">
                        <div class="grid_img">
                            <img src="./images/snowboard.png" alt="#" class="card-img">
                        </div>
                        <div class="txt_img">
                            <h3>Велосервис</h3>
                            <p>Оперативный и качественный ремонт вашего велосипеда с выгодными условиями</p>
                        </div>
                    </div>
    
                    <div class="grid_img-card">
                        <div class="grid_img">
                            <img src="./images/mask.png" alt="#" class="card-img">
                        </div>
                        <div class="txt_img">
                            <h3>Велозапчасти</h3>
                            <p>В нашем ассортименте имеется огромный выбор недорогих оригинальных деталей</p>
                        </div>
                    </div>
    
                    <div class="grid_img-card">
                        <div class="grid_img">
                            <img src="./images/child.png" alt="#" class="card-img">
                        </div>
                        <div class="txt_img">
                            <h3>Продажа б/у велосипедов</h3>
                            <p>Продаём исправные велосипеды прошлых сезонов, в том числе детские.</p>
                        </div>
                    </div>
    
                </div>
            </div>
        </div>
    </div>

</template>

<style>
.content_block{
    width: 100%;
    max-width: 80.5rem;;
    margin: 7.5rem auto;
}

.content_services{
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 1.5rem;
}

.card-img{
    width: 23.75rem;
    height: 14.625rem;
    border-radius: 0.9rem;
}

.card_grid{
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.3rem;
}
</style>