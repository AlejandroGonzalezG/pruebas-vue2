<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Carrousel>
    </Carrousel>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import Carrousel from '@/components/navbar.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    Carrousel
  }
}
</script>
