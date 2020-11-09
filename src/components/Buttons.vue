<template>
  <div>
    <slot name="green"></slot>
    <slot name="red"></slot>
    <slot name="blue"></slot>
  </div>
</template>
<script>
export default {
  name: 'Buttons',
    }
</script>
<style>
.Red{
  width:120px;
  height: 50px;
  margin: 50px;
  padding: 10px;
  background-color:red;
  text-align: center;
  cursor:pointer;
}
.Green{
  width:120px;
  height: 50px;
  margin: 50px;
  padding: 10px;
  background-color:Green;
  text-align: center;
  cursor:pointer;
}
.Blue{
  width:120px;
  height: 50px;
  margin: 50px;
  padding: 10px;
  background-color:blue;
  text-align: center;
  cursor:pointer;
}
</style>