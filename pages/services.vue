<template>
  <transition mode="out-in">
    <section class="container">
      services
    </section>
  </transition>
</template>

<script>
    export default {
      transition(to, from) {
        if (!from) return 'slide-left';
        return +to.query.page < +from.query.page ? 'slide-right' : 'slide-left'
      },
      name: "services"
    }
</script>

<style scoped>

</style>
