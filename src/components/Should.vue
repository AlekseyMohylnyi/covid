,<template>
    <section class="should">
        <h4 class="should__subtitle">Covid-19</h4>
        <h2 class="should__title">What  should we do</h2>
        <p class="should__text">Corona viruses are a type of virus. There are many different kinds, and some cause disease. A newly identified type has caused</p>
        <div class="should__items">
            <div class="should__item">
                <div class="should__info">
                    <div class="should__item-num">01</div>
                    <div class="should__item-title">Wear Masks</div>
                    <div class="should__item-text">Continually seize impactful vortals rather than future-proof supply chains. Uniquely exploit emerging niches via fully tested meta-services. Competently pursue standards compliant leadership skills vis-a-vis pandemic "outside the box" thinking. Objectively </div>
                </div>           
                <div class="should__img">
                    <img src="../assets/images/Mask.png" alt="img">
                </div>                
            </div>
            <div class="should__item">
                <div class="should__img">
                    <img src="../assets/images/Wash.png" alt="img">
                </div>  
                <div class="should__info">
                    <div class="should__item-num">02</div>
                    <div class="should__item-title">Wash Your Hands</div>
                    <div class="should__item-text">Continually seize impactful vortals rather than future-proof supply chains. Uniquely exploit emerging niches via fully tested meta-services. Competently pursue standards compliant leadership skills vis-a-vis pandemic "outside the box" thinking. Objectively Continually seize impactful vortals </div>
                </div>       
            </div>
            <div class="should__item">
                <div class="should__info">
                    <div class="should__item-num">03</div>
                    <div class="should__item-title">Use nose -  rag</div>
                    <div class="should__item-text">Continually seize impactful vortals rather than future-proof supply chains. Uniquely exploit emerging niches via fully tested meta-services. Competently pursue standards compliant leadership skills vis-a-vis pandemic "outside the box" thinking. Objectively</div>
                </div>           
                <div class="should__img">
                    <img src="../assets/images/Sneeze.png" alt="img">
                </div>                
            </div>
            <div class="should__item">
                <div class="should__img">
                    <img src="../assets/images/Hand girl.png" alt="img">
                </div>   
                <div class="should__info">
                    <div class="should__item-num">04</div>
                    <div class="should__item-title">Avoid contacts</div>
                    <div class="should__item-text">Continually seize impactful vortals rather than future-proof supply chains. Uniquely exploit emerging niches via fully tested meta-services. Competently pursue standards compliant leadership skills vis-a-vis pandemic</div>
                </div>                             
            </div>
            <img class="should__virus should__virus-one" src="../assets/images/should-virus1.svg" alt="virus">
            <img class="should__virus should__virus-two" src="../assets/images/should-virus2.svg" alt="virus">
            <img class="should__virus should__virus-three" src="../assets/images/should-virus3.svg" alt="virus">
        </div>
    </section>
</template>

<style>
.should {
  margin: 200px auto;
  position: relative;
}

.should__subtitle {
  font-family: 'Red Hat Display';
  font-weight: 700;
  margin-bottom: 5px;
  color: var(--red);
  font-size: 1.5rem;
  text-align: center;
}

.should__title {
  font-family: 'Red Hat Display';
  margin-bottom: 3rem;
  color: var(--black);
  font-weight: 700;
  font-size: 3.1rem;
  line-height: 1;
  text-align: center;
}

.should__text {
  font-weight: 500;
  margin-bottom: 54px;
  font-size: 1.125rem;
  line-height: 1.5;
  text-align: center;
  max-width: 570px;
  margin: 0 auto 4rem;
}

.should__items {   
  padding: 0 20rem 0 15rem;  
}

.should__item {
  display: grid;
  grid-template-columns: 1fr 1fr;   
}

.should__info {
    display: grid;
    grid-template-columns: 1fr 6fr;
    grid-template-rows: 1fr 1fr 3fr;
    grid-template-areas: '. .' 'num title' '. text';
}

.should__item-num {
    grid-area: num;
    align-self: center;
    color: var(--active);
    font-weight: 700;
    font-size: 2.75rem;        
    background: pink;
    border-radius: 50%;
    width: 75px;
    height: 75px;
    display: grid;
    text-align: center;    
    align-content: center;    
    padding-left: 4px;
}

.should__item-title {
    grid-area: title;
    padding-left: 2rem;
    align-self: center;
    font-size: 2.9rem;
    font-weight: 500;
    line-height: 69px;    
}

.should__item-text {
    padding-left: 2rem;
    grid-area: text;
    font-size: 1.1rem;
    line-height: 40px;
    text-transform: capitalize;
}

.should__img {
    text-align: center;
}

.should__virus {
    position: absolute;
}

.should__virus-one {
    left: 0;
    top:550px;
}

.should__virus-two {
    right: 0;
    bottom: 250px;
}

.should__virus-three {
    right: 40px;
    bottom: 570px;
}
</style>