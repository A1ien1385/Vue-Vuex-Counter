<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <counter />
    <counterSquared />
    <buttons />
    <inputs />
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  
  components: {
    'counter': require('@/components/Counter.vue').default,
    'counterSquared': require('@/components/CounterSquared.vue').default,
    'buttons': require('@/components/Buttons.vue').default,
    'inputs': require('@/components/Input.vue').default
  }
}
</script>

<style>
div {
  margin-bottom: 10px;
}

.counter {
  font-size: 80px;
}

.buttons button {
  font-size: 40px;
  width: 100px;
  margin: 0 10px;
}
</style>