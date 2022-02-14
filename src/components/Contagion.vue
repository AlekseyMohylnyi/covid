<template>
    <section class="contagion">
        <h4 class="contagion__subtitle">Covid-19</h4>
        <h2 class="contagion__title">Contagion</h2>
        <p class="contagion__text">Corona viruses are a type of virus. There are many different kinds, and some cause disease. A newly identified type</p>
        <img class="contagion__img-top" src="../assets/images/contagion-virus1.svg" alt="img">
        <img class="contagion__img-bottom" src="../assets/images/contagion-virus2.svg" alt="img">
        <div class="contagion__cards">
            <div class="card">
                <img class="card__img" src="../assets/images/contagion1.png" alt="img">
                <h3 class="card__title">Air Transmission</h3>
                <p class="card__text">Objectively evolve tactical expertise before extensible initiatives. Efficiently simplify</p>
            </div>
            <div class="card active">
                <img class="card__img" src="../assets/images/contagion2.png" alt="img">
                <h3 class="card__title">Human Contacts</h3>
                <p class="card__text">Washing your hands is one of thesimplest ways you can protect</p>
            </div>
            <div class="card">
                <img class="card__img" src="../assets/images/contagion3.png" alt="img">
                <h3 class="card__title">Containted Objects</h3>
                <p class="card__text">Use the tissue while sneezing,In this way, you can protect your droplets.</p>
            </div>
        </div>
    </section>
</template>

<style>
.contagion {       
    margin-top: 30px;    
    position: relative;
    margin-bottom: 9.25rem;    
}

.contagion__subtitle {
  font-family: 'Red Hat Display';
  font-weight: 700;
  margin-bottom: 5px;
  color: var(--red);
  font-size: 1.5rem;
  text-align: center;
}

.contagion__title {
  font-family: 'Red Hat Display';
  margin-bottom: 3rem;
  color: var(--black);
  font-weight: 700;
  font-size: 3.1rem;
  line-height: 1;
  text-align: center;
}

.contagion__text {
  font-weight: 500;
  margin-bottom: 54px;
  font-size: 1.125rem;
  line-height: 38px;
  text-align: center;
  max-width: 570px;
  margin: 0 auto 4rem;
}

.contagion__img-top {
    position: absolute;
    top: -90px;
    right: 85px;
}

.contagion__img-bottom {
    position: absolute;
    bottom: 40px;
    left: 100px;
    z-index: -22;
}

.contagion__cards {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-gap: 30px;
    padding: 0 240px;
}

.card {
    background-color: var(--white);
    text-align: center;
    padding: 2rem 3.2rem 3.5rem;
    display: flex;
    flex-direction: column;
    justify-content: end;
    box-shadow: 0px 5px 80px rgba(0, 0, 0, .08);
}

.card__title {
    font-weight: 500;
    font-size: 2rem;
    line-height: 53px;
}

.card__img {
    margin-bottom: 3.6rem;
}

.card__text {
    font-size: 1.1rem;
    line-height: 33px;
}

.active {
    border-bottom: 6px solid var(--active);
}
</style>