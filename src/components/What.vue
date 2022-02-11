<template>
    <section class="what">
        <img class="what__img" src="../assets/images/What-img.png" alt="img">
        <div class="what__info">            
            <h4 class="what__subtitle">What Is Covid-19</h4>
            <h1 class="what__title">Coronavirus</h1>
            <p class="what__text">Corona viruses are a type of virus. There are many different kinds, and some cause disease. A newly identified type has caused a recent outbreak of respiratory illness now called COVID-19.Lauren Sauer, M.S., the director of operations with the Johns Hopkins Office of Critical Event Preparedness and Response</p>
            <a class="btn what__btn" href="#">Learn More</a>
            <img class="what__virus" src="../assets/images/what-virus.svg" alt="img">
      </div>
    </section>
</template>

<style>
.what {
  overflow: hidden;
  display: grid;
  grid-template-columns: 1fr 1fr;
  padding: 0 240px 0 0; 
}

.what__info {
  display: flex;
  flex-direction: column;
  justify-content: center;   
  position: relative;
  padding: 10rem 0;
}
.what__virus {
  width: 290px;
  height: 290px;
  position: absolute;
  bottom: 115px;
  right: -310px;  
  transform: rotate(30deg);
}

.what__img {
  transform: rotate(25deg);
}

.what__subtitle {
  font-family: 'Red Hat Display';
  font-weight: 700;
  margin-bottom: 5px;
  color: var(--red);
  font-size: 1.5rem;
}

.what__title {
  font-family: 'Red Hat Display';
  margin-bottom: 30px;
  color: var(--black);
  font-weight: 700;
  font-size: 3.1rem;
  line-height: 1;
}

.what__text {
  margin-bottom: 54px;
  font-size: 1.5rem;
  line-height: 2;
}

.what__btn {
  background: rgba(250, 86, 82, 0.15);
  border-radius: 65px;
  color: var(--red);
}
</style>