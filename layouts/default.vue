<template>
  <div>
    <MainHeader />
    <Nuxt />
    <MainFooter />
  </div>
</template>

<script>
import MainHeader from '@/components/layouts/header'
import MainFooter from '@/components/layouts/footer'
import '../assets/styles/index.scss'

export default {
  components: {
    MainHeader,
    MainFooter,
  },
}
</script>
