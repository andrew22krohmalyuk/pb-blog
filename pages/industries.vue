<template>
  <section class="container">
    industries
  </section>
</template>

<script>
    export default {
      transition(to, from) {
        if (!from) return 'slide-left'
        return +to.query.page < +from.query.page ? 'slide-right' : 'slide-left'
      },
      name: "industries"
    }
</script>

<style scoped>

</style>
