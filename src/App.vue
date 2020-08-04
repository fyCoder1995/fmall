<template>
  <div id="app">
    <ul>
      <li v-for="(item,index) in 100" :key="index">
        {{item}}
      </li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
</style>
