<template>
  <RouterView class="app antialiased bg-white text-on-dark" v-cloak />
</template>

<script>
export default {
  name: 'App',
  metaInfo () {
    return {
      title: 'Frontend by mudhead'
    }
  }
}
</script>

<style src="./assets/css/tailwind.css"></style>
