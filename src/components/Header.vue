<template>
  <header class="header">
    <container>
      <div class="header__wrp">
        <router-link to="/" class="header-logo">
          <img src="@/assets/img/weather-logo.png" alt="weather" class="header-logo__img">
          <div class="header-logo__title">weather</div>
        </router-link>
        <div class="header-menu">
          <v-link
            to=""
            class="header-menu__button button--primary"
            title="Login"
          />
          <v-link
            to=""
            class="header-menu__button button--green"
            title="Register"
          />
        </div>
      </div>
    </container>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped lang="scss">
@import "../assets/scss/components/header";
</style>
