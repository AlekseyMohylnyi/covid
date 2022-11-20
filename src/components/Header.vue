<template>  
    <header class="header">      
      <div class="header__info">
        <img class="header__img" src="../assets/images/virus-one.svg" alt="img">
        <h4 class="header__subtitle">COVID-22 Alert</h4>
        <h1 class="header__title">Stay at Home quarantine <br/> To stop Corona virus</h1>
        <p class="header__text">There is no specific medicine to prevent or treat coronavirus  disease (COVID-22). People may need supportive care to.</p>
        <a class="btn header__btn" href="#">Let Us Help</a>
      </div>
      <div class="header__img">
        <img src="../assets/images/header-bg.png" alt="img">
      </div>
    </header>  
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>

.header {  
  padding-left: 243px;  
  padding: 3.5rem 0 0 243px;
  display: grid;
  grid-template-columns: 1fr 1fr;
}

.header__info {
  display: flex;
  flex-direction: column;
  justify-content: end; 
  padding-bottom: 105px; 
  position: relative;
}

.header__info img {
  width: 189px;
  height: 193px;
  position: absolute;
  top: 48px;
  right: -70px;
}

.header__subtitle {
  font-family: 'Red Hat Display';
  font-weight: 700;
  margin-bottom: 15px;
  color: var(--red);
  font-size: 2.2rem;
}

.header__title {
  font-family: 'Red Hat Display';
  margin-bottom: 30px;
  color: var(--black);
  font-weight: 700;
  font-size: 3.25rem;
  line-height: 1.25;
}

.header__text {
  margin-bottom: 54px;
  font-size: 1.5rem;
  line-height: 1.5;
}
</style>
