<script>

</script>

<template>
    <div class="slider_content">

        <div class="button_block">

            <div class="aline_items-button">
                <h2>Новости</h2>
    
                <div class="buttons">
                    <button>
                        <-
                    </button>
        
                    <button>
                        ->
                    </button>
                </div>
            </div>
        </div>

        <div class="slider_grid">
            <div class="slide_card">
                <a href="#" class="link_card">
                    <div class="status">
                        <p class="status_txt">
                            Объявление
                        </p>
                    </div>
                    <h3 class="status_header">
                        Роликовые коньки временно недоступны для проката
                    </h3>
                    <p class="status_text">
                        В связи с ремонтными работами в помещении проката роликовые коньки временно недоступны для проката.
                    </p>
                </a>
            </div>
    
            <div class="slide_card">
                <a href="#" class="link_card">
                    <div class="status">
                        <p class="status_txt">
                            Объявление
                        </p>
                    </div>
                    <h3 class="status_header">
                        Роликовые коньки временно недоступны для проката
                    </h3>
                    <p class="status_text">
                        В связи с ремонтными работами в помещении проката роликовые коньки временно недоступны для проката.
                    </p>
                </a>
            </div>
    
            <div class="slide_card">
                <a href="#" class="link_card">
                    <div class="status">
                        <p class="status_txt">
                            Объявление
                        </p>
                    </div>
                    <h3 class="status_header">
                        Роликовые коньки временно недоступны для проката
                    </h3>
                    <p class="status_text">
                        В связи с ремонтными работами в помещении проката роликовые коньки временно недоступны для проката.
                    </p>
                </a>
            </div>
        </div>
    </div>
</template>

<style>

.slider_content{
    width: 100%;
    max-width: 80.5rem;
    margin: 0 auto;
}

.aline_items-button{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.slider_grid{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 1.5rem;
    margin-top: 2.8rem;
}

/*Card*/
.link_card{
    text-decoration: none;
}

.status{
    background-color: #5B7DDE;
    padding: 0.75rem 0.75rem;
    width: 6.9rem;
    height: 1.2rem;
    border-radius: 1.5rem;
}

.status_txt{
    text-align: center;
    font-weight: 500;
    color: white;
    font-size: 1.06rem;
}

.status_header{
    font-weight: 700;
    font-size: 1.125rem;
    margin-top: 1.5rem;
    color: black;
}

.status_text{
    margin-top: 0.75rem;
    font-weight: 500;
    font-size: 1rem;
    color: #454F5B;
}

</style>