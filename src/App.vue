<template>
  <div id="app">
    <Header></Header>
    <router-view />
  </div>
</template>

<script>
import Header from '@/components/header/Header'
export default {
  name: 'APP',
  components: {
    Header
  }
}
</script>
<style>

</style>
