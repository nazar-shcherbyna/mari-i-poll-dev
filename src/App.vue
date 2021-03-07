<template>
  <div class="">
    <Header />
    <main class="container">
      <router-view/>
    </main>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'

export default {
  components: {
    Header
  }  
}
</script>
