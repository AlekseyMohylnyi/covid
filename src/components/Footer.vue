<template>
    <footer class="footer">
        <img class="footer__virus1" src="../assets/images/footer-virus1.svg" alt="virus">
        <img class="footer__virus2" src="../assets/images/footer-virus2.svg" alt="virus">
        <h2 class="footer__subtitle">Have Question in mind?</h2>
        <h2 class="footer__title">Let us help you</h2>
        <div class="footer__contacts">
            <a class="footer__email" href="#">snmonydemo@gmail.com</a>
            <a class="btn footer__btn" href="#">Send</a>
        </div>
        <div class="footer__nav">
            <a href="#" class="footer__logo">
                <img src="../assets/images/logo.png" alt="logo">                
            </a>
            <div class="footer__links">
                <a class="footer__nav-link" href="#">Overview</a>
                <a class="footer__nav-link" href="#">Symptoms</a>
                <a class="footer__nav-link" href="#">Prevention</a>
                <a class="footer__nav-link" href="#">Treatment</a>
            </div>  
            <div class="footer__icons">
                <a class="footer__icon" href="#">
                    <img src="../assets/images/icons/1.svg" alt="1">
                </a>
                <a class="footer__icon" href="#">
                    <img src="../assets/images/icons/2.svg" alt="2">
                </a>
                <a class="footer__icon" href="#">
                    <img src="../assets/images/icons/3.svg" alt="3">
                </a>
                <a class="footer__icon" href="#">
                    <img src="../assets/images/icons/4.svg" alt="4">
                </a>
            </div>
        </div>
        <div class="footer__rights">
            2022 @ All rights reserved by pixelspark.co
        </div>
    </footer>
</template>

<style>
.footer {
    margin: 200px auto;
    text-align: center;
    position: relative;
}

.footer__virus1 {
    position: absolute;
    right: 0;
    bottom: 150px;
}

.footer__virus2 {
    position: absolute;
    right: 140px;
    bottom: 500px;
}

.footer__subtitle {
    font-weight: 500;
    font-size: 4rem;
    line-height: 77px;
    color: var(--green);
}

.footer__title {
    font-weight: 600;
    font-size: 4rem;
    line-height: 77px;
    margin-bottom: 3.9rem;
    color: var(--green);
}

.footer__contacts {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 80px;
    padding: 0 37.7rem;
    margin-bottom: 11.3rem;
}

.footer__email {
   color: #758681;
   font-size: 22px;  
}

.footer__btn {    
    padding: 26px 80px;
}

.footer__nav {
    padding: 0 240px;
    display: flex;
    justify-content: space-between;   
    align-items: center;
    margin-bottom: 2rem;
}

.footer__logo {
    
}

.footer__links {
    display: flex;
    justify-content: space-between;
}

.footer__nav-link {
    margin-right: 3rem;
    font-size: 1.4rem;
    transition: all ease .2s;
}

.footer__nav-link:hover {
    opacity: .8;
}

.footer__nav-link:last-child {
     margin-right: 0;
}

.footer__icon {
    margin-right: 2rem;
}

.footer__icon:last-child {
    margin-right: 0;
}

.footer__rights {
    font-size: 1.4rem;
    font-weight: 600;
    padding-bottom: 2rem;
}
</style>