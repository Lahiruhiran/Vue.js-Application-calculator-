<template>
  <div class ="calculator">
<span>Hello</span>
<span>Hello</span>
<span>Hello</span>
<span>Hello</span>
<span>Hello</span>
<span>Hello</span>
<span>Hello</span>
<span>Hello</span>
    
     
  </div>
</template>

<script>
export default {
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.calculator{
  display: grid;
  grid-template-columns :repeat(4,1fr);
  grid-auto-rows: minmax(50px,auto);
}
</style>
