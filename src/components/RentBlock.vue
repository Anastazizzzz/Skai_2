<script>

</script>

<template>
    <div class="rent-content">
        <div class="rent-content__grid">
            <div class="frirst-grid-line">

                <div class="cardRent">
                    <div class="card-img">

                        <div class="img-block">
                            <img src="./images/forest.png" alt="#" class="background-img">
                        </div>

                        <div class="button-block">
                            <button class="arrow"><img src="" alt=""></button>
                        </div>

                    </div>

                    <div class="card-txt">

                        <h3>Беговые лыжи</h3>
                        <p>Пластиковые и полупластиковые лыжи для катания свободным и классическим стилем</p>

                    </div>

                </div>

                <div class="cardRent">

                    <div class="card-img">

                        <div class="img-block">
                            <img src="./images/snowboard.png" alt="#" class="background-img">
                        </div>

                        <div class="button-block">
                            <button class="arrow"><img src="" alt=""></button>
                        </div>

                    </div>

                    <div class="card-txt">

                        <h3>Сноуборды</h3>
                        <p>В наличии все размеры, разные типы креплений, доски для новичков</p>

                    </div>

                </div>

                <div class="cardRent">
                    <div class="card-img">

                        <div class="img-block">
                            <img src="./images/skis.png" alt="#" class="background-img">
                        </div>

                        <div class="button-block">
                            <button class="arrow"><img src="" alt=""></button>
                        </div>

                    </div>

                    <div class="card-txt">

                        <h3>Горные лыжи</h3>
                        <p>Широкая линейка размеров, в том числе детские</p>

                    </div>

                </div>

            </div>
<!------------------------------------------------------------------------------------------------------>
            <div class="second-grid-line">
                <div class="card-img-second">

                    <div class="cardRent">
                        <div class="card-img">

                            <div class="img-block">
                                <img src="./images/mask.png" alt="#" class="background-img">
                            </div>

                            <div class="button-block">
                                <button class="arrow"><img src="" alt=""></button>
                            </div>

                        </div>

                        <div class="card-txt">

                            <h3>Горные лыжи</h3>
                            <p>Широкая линейка размеров, в том числе детские</p>

                        </div>
                    </div>
<!---------------------------------------------------------------------------------------------------->

                    <div class="cardRent">
                        <div class="card-img">

                            <div class="img-block">
                                <img src="./images/child.png" alt="#" class="background-img">
                            </div>

                            <div class="button-block-second">
                                <button class="arrow"><img src="" alt=""></button>
                            </div>

                        </div>

                        <div class="card-txt">

                            <h3>Горные лыжи</h3>
                            <p>Широкая линейка размеров, в том числе детские</p>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<style>

.rent-content__grid{
    width: 100%;
    max-width: 80.5rem;
    margin: 0 auto;
}

/*First line*/

.frirst-grid-line{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 1.8rem;
}

.img-block{
    position: relative;
    z-index: 1;
}

.background-img{
    border-radius: 0.9rem;
}

.button-block{
    position: absolute;
    margin: -2.4rem 0 0 23.7rem;
    z-index: 2;
}

.card-txt{
    background-color: rgba(244, 246, 248, 1);
    margin: 0;
    border-radius: 0.9rem;
    padding: 1.125rem;
}

/*Second line*/

.card-img-second{
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.8rem;
    margin-top: 1.8rem;
}

</style>