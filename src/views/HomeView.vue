<template>
  <div class="home">
    <div class="container">
      <Information></Information>
      <Sabores></Sabores>
      <Adornos></Adornos>
      <FormUser></FormUser>
      <Footer></Footer>
    </div>

  </div>
</template>

<script>
import Information from '@/components/Info.vue';
import Sabores from '@/components/Sabores.vue';
import Adornos from '@/components/Adornos.vue';
import FormUser from '@/components/FormUser.vue';
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    Information,
    Sabores,
    Adornos,
    FormUser,
    Footer
  }
}
</script>
