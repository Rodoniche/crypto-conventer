<script>
import Input from './components/Input.vue';
import selector from './components/selector.vue';
export default {
  components: { Input, selector },
}
</script>

<template>
  <h1>crypto</h1>
  <Input/>
  
  <div className="selectors">
    <selector/>
    <selector/>

  </div>


</template>

<style scoped>


.selectors {
  
  display: flex;
  place-content: center;

  justify-content: space-around;
  width: 650px;
  margin: 0 auto;
 
  
  
  
}




</style>
