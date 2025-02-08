<script setup>

</script>

<template>
    <body>
        <div class="menu-components">
            <h2>Прокат <span>летнего инвентаря</span> <img src="./images/sun.png" alt=""></h2>
            <div class="card-grid">
                <div class="first-line">
                    <div class="card">
                        <img src="./images/img1.png" alt="">
                        <div class="txt-desc">
                            <div class="txt-content">
                                <h3>Велосипеды</h3>
                                <p>Прокат велосипедов, удобное расположение</p>
                            </div>
                        </div>
                    </div>
                    <div class="card">
                        <img src="./images/img2.png" alt="">
                        <div class="txt-desc">
                            <div class="txt-content">
                                <h3>Роликовые коньки</h3>
                                <p>Широкая размерная линейка, в том числе детские.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="second-line">
                    <div class="card">
                        <img src="./images/img3.png" alt="">
                        <div class="txt-desc">
                            <div class="txt-content">
                                <h3>Самокаты</h3>
                                <p>Электрические самокаты для скоростных прогулок.</p>
                            </div>
                        </div>
                    </div>
                    <div class="card">
                        <img src="./images/img4.png" alt="">
                        <div class="txt-desc">
                            <div class="txt-content">
                                <h3>Детскиее электромобили</h3>
                                <p>Порадуйте своего ребенка поездкой на электромашинке!</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </body>
</template>

<style scoped>

.menu-components{
    width: 100%;
    max-width: 80.5rem;
    margin: 0 auto;
}

.card-grid{
    display: grid;
    grid-template-rows: 1fr 1fr;
    gap: 1rem;
}

.first-line{
    margin-top: 12.3125rem;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
}

.second-line{
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
}

.txt-desc{
    width: 39.375rem;
    height: 5.1875rem;
    background-color: rgba(244, 246, 248, 1);
}

.txt-content{
    padding: 1.125rem;
}

</style>
