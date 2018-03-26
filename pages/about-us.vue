<template>
  <section class="container">
    company
  </section>
</template>

<script>
    export default {
      transition(to, from) {
        if (!from) return 'slide-left'
        return +to.query.page < +from.query.page ? 'slide-right' : 'slide-left'
      },
      name: "company"
    }
</script>

<style scoped>

</style>
