<template>
    <section class="reports">        
        <div class="reports__img">
            <img src="../assets/images/Map.png" alt="map">
        </div>
        <div class="reports__info">
            <div class="reports__top">
                <h4 class="reports__title">Live Reports</h4>
            <a class="reports__arrow" href="#"> 
                <img src="../assets/images/icons/arrow-lefr.svg" alt="arrow">
            </a>
            <a class="reports__arrow" href="#">
                <img src="../assets/images/icons/arrow-right.svg" alt="arrow">
            </a>
            </div>            
            <div class="reports__country">
                <div class="reports__item">
                    <div class="reports__flag">
                        <img src="../assets/images/icons/usa.svg" alt="usa">
                    </div>
                    <div class="reports__name">USA</div>
                    <div class="reports__sick">100,392</div>
                    <div class="report__arrow">
                        <img src="../assets/images/icons/arrow-up.svg" alt="up">
                    </div>
                </div>
                <div class="reports__item">
                    <div class="reports__flag">
                        <img src="../assets/images/icons/italy.svg" alt="italy">
                    </div>
                    <div class="reports__name">Italy</div>
                    <div class="reports__sick">87,445</div>
                    <div class="report__arrow">
                        <img src="../assets/images/icons/arrow-up.svg" alt="up">
                    </div>
                </div>
                <div class="reports__item">
                    <div class="reports__flag">
                        <img src="../assets/images/icons/china.svg" alt="china">
                    </div>
                    <div class="reports__name">China</div>
                    <div class="reports__sick">81,330</div>
                    <div class="report__arrow">
                        <img src="../assets/images/icons/arrow-down.svg" alt="down">
                    </div>
                </div>
                <div class="reports__item">
                    <div class="reports__flag">
                        <img src="../assets/images/icons/spain.svg" alt="spain">
                    </div>
                    <div class="reports__name">Spain</div>
                    <div class="reports__sick">64,059</div>
                    <div class="report__arrow">
                        <img src="../assets/images/icons/arrow-up.svg" alt="up">
                    </div>
                </div>
                <div class="reports__item">
                    <div class="reports__flag">
                        <img src="../assets/images/icons/germany.svg" alt="germany">
                    </div>
                    <div class="reports__name">Germany</div>
                    <div class="reports__sick">50,871</div>
                    <div class="report__arrow">
                        <img src="../assets/images/icons/arrow-up.svg" alt="up">
                    </div>
                </div>
                <div class="reports__item">
                    <div class="reports__flag">
                        <img src="../assets/images/icons/iran.svg" alt="iran">
                    </div>
                    <div class="reports__name">Iran</div>
                    <div class="reports__sick">32,332</div>
                    <div class="report__arrow">
                        <img src="../assets/images/icons/arrow-up.svg" alt="up">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style>
    .reports {
        margin: 200px auto;
        display: grid;
        grid-template-columns: 67% 33%;        
        align-items: center;
        
    }

    .reports__top {
        display: flex;        
        align-items: center;
        margin-bottom: 2rem;
    }

     a:first-child {
        position: relative;
        margin-right: 2rem

    }
    .reports__top a:first-child:after {
        position: absolute;

        
    }

    .reports__title {
        font-size: 3rem;
        line-height: 58px;
        font-weight: 500;
        margin-right: 50px;
    }

    .reports__item {
        display: grid;
        grid-template-columns: 1fr 3fr 1fr 1fr;
        margin-bottom: 1.5rem;        
        align-items: center;
    }

    
</style>