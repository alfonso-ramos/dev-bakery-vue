<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Information></Information>
    <Sabores></Sabores>
    <Adornos></Adornos>
  </div>
</template>

<script>
import Information from '@/components/Info.vue';
import Sabores from '@/components/Sabores.vue';
import Adornos from '@/components/Adornos.vue'

export default {
  name: 'HomeView',
  components: {
    Information,
    Sabores,
    Adornos
  }
}
</script>
