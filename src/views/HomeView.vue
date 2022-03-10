<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <home-s/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeS from '@/components/home/Home.vue'

export default {
  name: 'HomeView',
  components: {
    HomeS
  }
}
</script>
