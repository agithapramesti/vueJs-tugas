<template>
  <div class="links">
    <router-link to="/">Home</router-link>
    <router-link to="/user-index">Customer</router-link>
  </div>
</template>
<script>
  export default {
    name: 'Link',
    data () {
      return {
        msg: 'This is awesome'
      }
    }
  }
</script>
