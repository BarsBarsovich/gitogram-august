<template>
  <div class="avatar">
    <img :src="url" alt="" class="avatar__icon">
    <p class="avatar__login">{{ name }}</p>
  </div>

</template>

<script>
export default {
  name: 'avatar',
  props: {
    name: {
      type: String,
      required: true
    },
    url: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped lang="scss">

</style>
