<template>
  <div class="p-3" style="max-width:400px; margin: 50px auto; background-color: #234 ">
   
   <!---calculator result-->
    
    <div class="w-full rounded m-1 p-3 text-right lead font-weight-bold text-white bg-vue-dark">
      0
    </div>

  </div>
</template>

<script>
export default {
  name: "Calculator",
  props: {
    msg: String,
  },
  data(){
 return{
   calculatorValue:'',
 }
  }
};
</script>

<style scoped>
.bg-vue-dark{
  background: #31475e;
}
</style>
