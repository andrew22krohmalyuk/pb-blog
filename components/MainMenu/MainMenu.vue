<template>
  <!-- main menu -->
  <div class="Main-menu Header__menu">
    <div class="Main-menu__item">
      <nuxt-link to="/" class="Main-menu__item-link">Home</nuxt-link>
    </div>
    <div class="Main-menu__item">
      <nuxt-link to="/services" class="Main-menu__item-link">
        Services
        <a>
                <span class="Main-menu__item-open-button-wrapper">
                    <img class="Main-menu__item-open-button" src="../../static/img/icons/arrow-down.svg" alt="">
                </span>
        </a>
      </nuxt-link>
      <div class="Main-menu__drop-down-menu">
        <nuxt-link to="dedicated-development-teams" class="Main-menu__dropdown-link">
          Dedicated Development Teams
        </nuxt-link>
        <nuxt-link to="web-development" class="Main-menu__dropdown-link">
          Web Development
        </nuxt-link>
        <nuxt-link to="mobile-development" class="Main-menu__dropdown-link">
          Mobile Development
        </nuxt-link>
        <nuxt-link to="custom-software-development" class="Main-menu__dropdown-link">
          Custom Software Development
        </nuxt-link>
        <nuxt-link to="business-intelligence-big-data-development" class="Main-menu__dropdown-link">
          BI & Big Data Development
        </nuxt-link>
      </div>
    </div>

    <div class="Main-menu__item">
      <nuxt-link to="/expertise" data-url="/expertise" class="Main-menu__item-link">
        Expertise
        <a>
                <span class="Main-menu__item-open-button-wrapper">
                    <img class="Main-menu__item-open-button" src="../../static/img/icons/arrow-down.svg" alt="">
                </span>
        </a>
      </nuxt-link>
      <div class="Main-menu__drop-down-menu">
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          AI & ML
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          BI & Data Science
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          IoT
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          Blockchain
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          Cloud & DevOps
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          UI/UX
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          Software & Hightech
        </nuxt-link>
      </div>
    </div>

    <div class="Main-menu__item">
      <nuxt-link to="/industries" class="Main-menu__item-link">
        Industries
        <a>
              <span class="Main-menu__item-open-button-wrapper">
                  <img class="Main-menu__item-open-button" src="../../static/img/icons/arrow-down.svg" alt="">
              </span>
        </a>
      </nuxt-link>
      <div class="Main-menu__drop-down-menu">
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          Business Software
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          Fintech
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          CRM/ERP
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          Retail
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          Travel & Hospitality
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          Media & Entertainment
        </nuxt-link>
        <nuxt-link to="coming-soon" class="Main-menu__dropdown-link">
          High-Tech
        </nuxt-link>
      </div>
    </div>
    <div class="Main-menu__item">
      <nuxt-link to="/case-studies" class="Main-menu__item-link">Case Studies</nuxt-link>
    </div>
    <div class="Main-menu__item">
      <nuxt-link to="/about-us" class="Main-menu__item-link">Company</nuxt-link>
    </div>
    <div class="Main-menu__item">
      <nuxt-link to="/blog" class="Main-menu__item-link">Blog</nuxt-link>
    </div>
    <nuxt-link to="/contact-us" class="Main-menu__make-request-btn Header__item-button">
      Make a Request
    </nuxt-link>
  </div>
  <!-- main menu end -->
</template>

<script>
    export default {
        name: "main-menu"
    }
</script>

<style lang="sass" scoped>
  @import 'MainMenu.scss'
</style>
