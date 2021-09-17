
<template>
  <div class="container">
    <div class="row">
        <div class="col-xs-12 col-sm-6 col-md-8 col-centered">
            <div class="maintxt">
                Elevate your Game !
            </div>
        </div>
    </div>
</div>
</template>

<style>
  .maintxt { 
    background-image: url="@/assets/home.webp";
    background-size: cover;
}


</style>


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
