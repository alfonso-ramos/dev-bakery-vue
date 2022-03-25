<template>
    <h2>Adornos</h2>
    <div class="adornos-container">
        <div class="adorno">
            <img src="../assets/letrero-fc.webp" alt="Adorno">
            <p>Letrero "Feliz Cumpleaños"</p>
            <p>$40</p>
            <button class="pedido">Agregar al carrito</button>
        </div>
        <div class="adorno">
            <img src="../assets/velas-piro.jpg" alt="Adorno">
            <p>Velas de vengala</p>
            <p>$20 C/unidad</p>
            <button class="pedido">Agregar al carrito</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Adornos'
}
</script>

<style>
    .adornos-container .adorno{
        padding: 2rem 3rem;
        border: 3px solid #42b983;
        border-radius: 2rem;
        margin-bottom: 4rem;
    }
    .adorno img{
        margin: 0 auto;
    }
    @media (min-width: 768px){
        .adornos-container{
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 4rem;
        }
    }
</style>