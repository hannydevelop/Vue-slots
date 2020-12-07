<template>
<div>
  <div>
    <h1 class="title">List of Different Forms Built With Vue-Slots</h1>
    <slot name="title1"></slot>
    <slot name="form1"></slot>
    <slot name="button1"></slot>
  </div>
  <div>
    <slot name="title2"></slot>
    <slot name="form2"></slot>
    <slot name="button2"></slot>
  </div>
  <div>
    <slot name="title3"></slot>
    <slot name="form3"></slot>
    <slot name="button3"></slot>
  </div>
</div>
</template>

<script>
export default {
  name: 'Forms',
    }
</script>

<style scoped>
.title{
  text-align: center;
}
</style>