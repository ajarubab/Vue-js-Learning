<template>
    <div class="guyz">
      <h1>{{ name }}</h1>
    </div>
  </template>

<script>
export default {
  name: 'HelloGuyz',
  props: {
    name: String
  }
}
</script>