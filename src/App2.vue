<template>
<h1>This is H1 tag in App2.vue</h1>
<HelloGuyz name="Hello guys how are you"/>
</template>

  
  
<script>
import HelloGuyz from './components/HelloGuyz.vue'

export default {
    name: 'App_two',
    components: {
        HelloGuyz
    }
}
</script>
  
  
<style>
  </style>
