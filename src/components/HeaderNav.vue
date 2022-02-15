<template>
    <nav class="nav">
        <a href="#" class="nav__logo">
            <img src="../assets/images/logo.png" alt="logo">                
        </a>
        <div class="nav__links">
            <a class="nav__link" href="#">Overview</a>
            <a class="nav__link" href="#">Contagion</a>
            <a class="nav__link" href="#">Simptoms</a>
            <a class="nav__link" href="#">Prevention</a>
            <a class="nav__btn" href="#">Contacts</a>
        </div>
    </nav>
</template>

<style>
.nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 2rem 15rem;
}

.nav__link {
    margin-right: 2rem;
    font-size: 1.2rem;
    font-weight: 600;
    transition: all ease .2s;
}

.nav__link:hover {
    opacity: .8;
}

.nav__btn {
    border: 1px solid var(--red);
    background-color: inherit;
    font-size: 1.2rem;
    font-weight: 600;
    color: var(--red);
    padding: 1rem 2.8rem;
    border-radius: 65px;
    transition: all ease .2s;
}

.nav__btn:hover {    
    background-color: var(--red);
    color: var(--white);    
}
</style>