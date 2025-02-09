<script>

</script>

<template>
    <div class="blog_content">
        <div class="content_grid">
            <div class="articles">

                <div class="articles_column">
                    <div class="articles-card">
                        <img src="./images/blog/img1.png" alt="#" class="card_img">

                        <div class="text">Как выбрать детские ролики напрокат?</div>
                    </div>

                    <div class="articles-card">
                        <img src="./images/blog/img2.png" alt="#" class="card_img">

                        <div class="text">Почему следует использовать специальные носки для роликов?</div>
                    </div>

                    <div class="lil_articles">
                        <div class="lil-card">
                            <img src="./images/blog/img3.png" alt="#" class="lil-card_img">

                            <div class="text">Что входит в горнолыжный инвентарь?</div>
                        </div>

                        <div class="lil-card">
                            <img src="./images/blog/img4.png" alt="#" class="lil-card_img">

                            <div class="text">Самостоятельная починка велосипеда или велосервис?</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<style>
.articles_column{
    width: 100%;
    max-width: 80.5rem;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 1.9rem;
    margin: 18rem auto;
}

/*Card Image*/

.card_img{
    width: 25.6rem;
    height: 29.25rem;
}
</style>