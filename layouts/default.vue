<template>
    <div id='app'>
    <HeaderNav />
    <Nuxt />
    <BottomNav/>
    </div>
</template>

<script>

import Header from '@/components/HeaderNav.vue'
import Bottom from '@/components/BottomNav.vue'

export default {
  components: {
    HeaderNav: Header,
    BottomNav: Bottom
  }

}
</script>