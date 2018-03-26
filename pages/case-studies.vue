<template>
  <section class="container">
    case studies
  </section>
</template>

<script>
    export default {
      transition(to, from) {
        if (!from) return 'slide-left';
        return +to.query.page < +from.query.page ? 'slide-right' : 'slide-left'
      },
      name: "case-studies"
    }
</script>

<style scoped>

</style>
