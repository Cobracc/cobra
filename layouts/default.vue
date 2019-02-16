<template>
  <div>
    <myheader></myheader>
    <nuxt />
    <myfooter></myfooter>  
  </div>
</template>


<script>
import myheader from '@/components/public/header/index.vue';
import myfooter from '@/components/public/footer/index.vue';
export default {
  components:{
    myheader,
    myfooter
  }
}
</script>
<style>

</style>
