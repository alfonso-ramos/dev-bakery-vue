<template>
  <div class="pastelero">
    <div class="container">
      <DispoSabores></DispoSabores>
      <DispoAdornos></DispoAdornos>
    </div>
  </div>
</template>

<script>
import DispoSabores from '@/components/DispoSabores.vue'
import DispoAdornos from '@/components/DispAdornos.vue'

export default {
  name: 'pastelero',
  components:{
    DispoSabores,
    DispoAdornos
  }
}
</script>

<style>

</style>
