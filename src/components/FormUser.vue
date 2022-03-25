<template>
  <div class="form-user">
    <label for="">Nombre (minimo un nombre y un apellido)</label>
    <input type="text" placeholder="Nombre">
    <label for="">No. de Telefono</label>
    <input type="number" placeholder="Ej. #6699667722">
    <label for="">Correo Electronico</label>
    <input type="email" placeholder="tucorreo@gmail.com">
  </div>
</template>

<script>
export default {
    name: 'FormUser'
}
</script>

<style>
  .form-user{
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  input{
    border: 2px solid #42b983;
    border-radius: .5rem;
  }
</style>