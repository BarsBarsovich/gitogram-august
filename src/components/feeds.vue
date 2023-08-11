<template>
  <h1 class="feeds-title">Hello from feeds</h1>
  <avatar name="Peter" url="https://via.placeholder.com/300/300"/>
</template>

<script>
import avatar from '@/components/avatar.vue'

export default {
  name: 'feeds',
  components: { avatar }
}
</script>

<style lang="scss">
.feeds-title {
  font-size: 32px;
}
</style>
