<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/bidbird.jpg">
    <HelloWorld msg="Welcome to BidBird App"/>
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
