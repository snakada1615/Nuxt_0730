<template>
  <div class="container">
    <TheNavbar />
    <main>
      <nuxt />
    </main>
  </div>
</template>

<script>
import TheNavbar from '@/components/TheNavbar'
export default {
  components: {
    TheNavbar,
  },
}
</script>

<style></style>
