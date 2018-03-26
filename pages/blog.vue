<template>
  <section class="container">
    blog
  </section>
</template>

<script>
    export default {
      transition(to, from) {
        if (!from) return 'slide-left';
        return +to.query.page < +from.query.page ? 'slide-right' : 'slide-left'
      },
      name: "blog"
    }
</script>

<style scoped>

</style>
