<template>
  <div class="container">
    
    <nuxt-link to="/products">products</nuxt-link>
    <nuxt-link to="/users">users</nuxt-link>


    <button type="button" @click="$router.push('/products')">Go to products</button>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
export default {
  components: {
    Header
  }
}
</script>
