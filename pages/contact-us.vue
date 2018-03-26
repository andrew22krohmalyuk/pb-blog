<template>
  <section class="container">
    contact us
  </section>
</template>

<script>
    export default {
      transition(to, from) {
        if (!from) return 'slide-left'
        return +to.query.page < +from.query.page ? 'slide-right' : 'slide-left'
      },
      name: "contact-us"
    }
</script>

<style scoped>

</style>
