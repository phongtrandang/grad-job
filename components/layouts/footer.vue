<template>
  <footer class="footer">
    <div class="container">Footer</div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  computed: {
    yearNow() {
      return new Date().getFullYear()
    },
  },
}
</script>
