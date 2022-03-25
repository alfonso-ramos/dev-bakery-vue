<template>
    <header>
        <div class="logo">
            <h1>Dev-Bakery</h1>
        </div>
        <div class="nav-container">
        <nav>
            <router-link to="/">Pasteleria</router-link> |
            <router-link to="/about">Pastelero</router-link>
        </nav>
        </div>
    </header>
    <router-view/>
</template>

<style>
:root{
    --mainFont: 'Ubuntu', sans-serif;
}
html{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-size: 62.5%;
}
*,*:before,*:after{
    box-sizing: inherit;
}
body{
    font-family: var(--mainFont);
    font-size: 1.6rem;
    line-height: 2rem;
}
/* Globales */
.container{
    max-width: 120rem;
    width: 90%;
    margin: 0 auto;
}
a{
    text-decoration: none;
}
h1{
    font-size: 4.8rem;
}
h2{
    font-size: 4rem;
}
img{
    max-width: 100%;
}
/* Utilities */
.no-margin{
    margin: 0;
}
.no-padding{
    padding: 0;
}
.text-center{
    text-align: center;
}
nav a.router-link-exact-active {
    color: #42b983;
}
/* Header section */
header{
    display: flex;
    flex-direction: column;
    text-align: center;
    margin-bottom: 4rem;
    -webkit-box-shadow: 0px 0px 16px -12px #000000; 
    box-shadow: 0px 6px 16px -12px #000000;
}
@media (min-width: 768px){
    header{
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
    }
}

</style>
