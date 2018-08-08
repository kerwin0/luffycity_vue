<template>
  <div id="app">
    <router-link to="/">吐槽</router-link>
    <router-link to="/course">课程</router-link>
    <router-link to="/news">so-tired</router-link>
    <router-link to="/login">登陆</router-link>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

</style>
