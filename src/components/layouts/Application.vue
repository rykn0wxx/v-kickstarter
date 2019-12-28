<template>
  <div class="layouts-application container">
    <div class="layouts-nav">
      <router-link to="/home">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'Application'
}
</script>

<style lang="scss" scoped></style>
