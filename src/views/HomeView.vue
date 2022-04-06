<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  
}
.home {
  display: flex;
  background: url("../assets/bg.jpg") no-repeat center;
  background-size: cover;
  background-attachment: fixed;
  height: 100vh;
  color: #fff;
  min-height: 500px;
  font-weight: 500;
}

</style>

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

