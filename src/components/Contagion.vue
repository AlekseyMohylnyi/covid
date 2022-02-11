<template>
    <section class="contagion">
        <h4 class="contagion__subtitle">Covid-19</h4>
        <h2 class="contagion__title">Contagion</h2>
        <p class="contagion__text">Corona viruses are a type of virus. There are many different kinds, and some cause disease. A newly identified type</p>
        <div class="contagion__cards">
            <div class="card">
                <img class="card__img" src="../assets/images/contagion1.png" alt="img">
                <h3 class="card__title">Air Transmission</h3>
                <p class="card__text">Objectively evolve tactical expertise before extensible initiatives. Efficiently simplify</p>
            </div>
            <div class="card">
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
    margin-top: 200px;
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
  margin-bottom: 30px;
  color: var(--black);
  font-weight: 700;
  font-size: 3.1rem;
  line-height: 1;
  text-align: center;
}

.contagion__text {
  margin-bottom: 54px;
  font-size: 1.5rem;
  line-height: 2;
  text-align: center;
}

.contagion__cards {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
}
</style>