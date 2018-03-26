<template>
  <section class="container">
    app
  </section>
</template>

<script>

  export default {
    transition(to, from) {
      if (!from) return 'slide-left'
      return +to.query.page < +from.query.page ? 'slide-right' : 'slide-left'
    },
    name: "index",
    components: {

    }
  }
</script>

<style>

</style>
