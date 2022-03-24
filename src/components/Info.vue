<template>
  <div class="info-container">
    <div class="info-img">
      <img src="../assets/pasteleria-interior.jpg" alt="Interior de pasteleria">
    </div>
    <div class="info">
      <p>Direccion: Blvd. Consquistadoes 1890, Ruta del Sol, Sta. Anita, 80058 Culiacan Rosales, Sin.</p>
      <p>Telefono: 6699667722</p>
      <p>Horario de atencion: 10:00 a.m. - 22:00 p.m.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Information'
}
</script>

<style>
  .info-container{
    display: flex;
    flex-direction: column;
  }
  .info-container .info-img img{
    width: 30rem;
    height: 20rem;
  }
</style>