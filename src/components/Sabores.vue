<template>
    <h2>Sabores</h2>
    <div class="sabores-container">
        <div class="sabor">
            <img src="../assets/pastel-chocolate.jpg" alt="Pastel de chocolate">
            <p>Pastel de chocolate</p>
            <p>$250</p>
            <button class="pedido">Agregar al carrito</button>
        </div>
        <div class="sabor">
            <img src="../assets/pastel-fresa.jpg" alt="Pastel de fresa">
            <p>Pastel de fresa</p>
            <p>$250</p>
            <button class="pedido">Agregar al carrito</button>
        </div>
        <div class="sabor">
            <img src="../assets/pastel-vainilla.jpg" alt="Pastel de vainilla">
            <p>Pastel de vainilla</p>
            <p>$250</p>
            <button class="pedido">Agregar al carrito</button>
        </div>
        <div class="sabor">
            <img src="../assets/red-velvet.jpg" alt="Pastel red velvet">
            <p>Pastel Red Velvet</p>
            <p>$300</p>
            <button class="pedido">Agregar al carrito</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Sabores'
}
</script>

<style>
    .sabores-container .sabor{
        padding: 2rem 3rem;
        border: 3px solid #42b983;
        border-radius: 2rem;
        margin-bottom: 4rem;
    }
    .sabores-container .sabor img{
        width: auto;
        height: auto;
    }
    .pedido{
        background-color: #551a8b;
        border: none;
        height: 3rem;
        padding: 0 1rem;
        color: white;
        font-weight: bold;
    }
    @media (min-width: 768px){
        .sabores-container{
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 4rem;
        }
    }
</style>