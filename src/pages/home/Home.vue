<template>
  <div>
    <!-- 这边为什么是home-header?? -->
    <home-header></home-header>
  </div>
</template>

<script>
import HomeHeader from '../home/components/Header'

export default {
  name: 'Home',
  components: {
    HomeHeader
  }

}
</script>
