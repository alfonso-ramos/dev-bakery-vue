<template>
  <div class="home">
    <div class="container">
      <Information></Information>
      <Sabores></Sabores>
      <Adornos></Adornos>
      <FormUser></FormUser>
    </div>

  </div>
</template>

<script>
import Information from '@/components/Info.vue';
import Sabores from '@/components/Sabores.vue';
import Adornos from '@/components/Adornos.vue';
import FormUser from '@/components/FormUser.vue';

export default {
  name: 'HomeView',
  components: {
    Information,
    Sabores,
    Adornos,
    FormUser
  }
}
</script>
