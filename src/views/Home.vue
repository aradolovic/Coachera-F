<template>
  <div class ="box" id="bg">
    <img src="@/assets/home.png"
    width="100%" 
    height="621"
     />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style>
  #bg {
  background: url("../assets/home.png") no-repeat center center fixed;
  -webkit-background-size : cover;
  -moz-background-size: cover;
  background-size: cover;
  -o-background-size: cover;

}
  .box {
  position:absolute;

  right:0px;
  bottom:0px;
  left:0px;
}
</style>