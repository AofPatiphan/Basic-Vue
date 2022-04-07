<template>
  <div class="home">
    <div class="vuelogo">
    <img alt="Vue logo" src="../assets/logo.png">
    </div>

    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style>

.vuelogo{
  display: flex;
  justify-content:center
}

</style>


