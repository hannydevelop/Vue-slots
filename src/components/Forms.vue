<template>
<div>
  <div>
    <slot name="title1"></slot>
    <h2>I am the form helper</h2>
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