
<template>
  <div id="app">
    <h1>Simple App that explains Vue Slots</h1>
    <Buttons>
    <button slot="green" class="Green">I am Green</button>
    </Buttons>
     <Buttons>
    <button slot="blue" class="Blue">I am Blue</button>
    </Buttons>
     <Buttons>
    <button slot="red" class="Red">I am Red</button>
    </Buttons>
    <Buttons>
    <button slot="red" class="Blue">I am Red</button>
    <button slot="red" class="Red">I am Red</button>
    <button slot="red" class="Green">I am Red</button>
    </Buttons>
  </div>
</template>
<script>
import Buttons from './components/Buttons'
export default {
  name: 'App',
  components: {
    Buttons,
  }
    }
</script>