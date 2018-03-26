<template>
  <div class="Header">
    <div class="Header__wrapper">

      <div class="Header__icon-container">
        <nuxt-link to="/">
          <img src="../../static/img/icons/perceptionbox-small-logo.svg" alt="Perceptionbox Logo" class="Header__icon">
        </nuxt-link>
      </div>

      <MainMenu />
      <BurgerMenu/>
    </div>
  </div>

</template>

<script>
  import MainMenu from '../../components/MainMenu/MainMenu';
  import BurgerMenu from '../../components/BurgerMenu/BurgerMenu';

  export default {
    components: {
      MainMenu,
      BurgerMenu
    }
  }

</script>

<style lang="sass" scoped>
  @import "Header"
</style>
