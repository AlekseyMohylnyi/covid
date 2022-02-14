<template>
    <section class="symptomps">
        <h4 class="symptomps__subtitle">Covid-19</h4>
        <h2 class="symptomps__title">Symptomps</h2>
        <p class="symptomps__text">Corona viruses are a type of virus. There are many different kinds, and some cause disease. A newly identified type has caused a recent outbreak of respiratory</p>
        <img class="symptomps__img-left" src="../assets/images/symptomps-virus2.svg" alt="img">
        <img class="symptomps__img-right" src="../assets/images/symptomps-virus1.svg" alt="img">
        <img class="symptomps__img" src="../assets/images/Simptomps.png" alt="img">
    </section>
</template>

<style>
.symptomps {
    margin: 200px 0;
    position: relative;
    text-align: center;
}

.symptomps__subtitle {
  font-family: 'Red Hat Display';
  font-weight: 700;
  margin-bottom: 5px;
  color: var(--red);
  font-size: 1.5rem;
  text-align: center;
}

.symptomps__title {
  font-family: 'Red Hat Display';
  margin-bottom: 3rem;
  color: var(--black);
  font-weight: 700;
  font-size: 3.1rem;
  line-height: 1;
  text-align: center;
}

.symptomps__text {
  font-weight: 500;
  margin-bottom: 54px;
  font-size: 1.125rem;
  line-height: 1.5;
  text-align: center;
  max-width: 570px;
  margin: 0 auto 4rem;
}

.symptomps__img-left {
    position: absolute;
    bottom: 195px;
    left: 0;
}

.symptomps__img-right {
    position: absolute;
    bottom: 0;
    right: 0;
}

</style>