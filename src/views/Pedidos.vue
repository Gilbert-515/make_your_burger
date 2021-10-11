<template>
  <div class="main-container">
    <h1>Gerenciar Pedidos:</h1>
    <DeashBoard/>
  </div>
</template>

<script>
import DeashBoard from '../components/DeashBoard.vue'

export default {
  name: 'Pedidos',

  components:{
    DeashBoard
  }
}
</script>