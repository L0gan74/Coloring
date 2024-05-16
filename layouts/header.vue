<script setup lang="ts">

import LogoSvg from '../public/icons/logo.svg'
import FormLoupe from '../public//icons/loupe.svg'

</script>

<template>
  <header class="header">
    <div class="header-top">
      <div class="header-top__search">
        <LogoSvg class="header-top__search-logo"/>
        <form class="header-top__search-form">
          <input class="header-top__search-input" type="text">
          <FormLoupe/>
          <button class="header-top__search-button" type="button">
            Найти
          </button>
        </form>
      </div>
    </div>
    <nav class="header-nav">
      <div class="header-nav__choose">
        <NuxtLink exact-active-class="_active" to="/categories" class="header-nav__choose-link">
          Рубрики
        </NuxtLink>
      </div>
      <div class="header-nav__choose">
        <NuxtLink exact-active-class="_active" href="" class="header-nav__choose-link">
          Блог
        </NuxtLink>
      </div>
      <div class="header-nav__choose">
        <NuxtLink exact-active-class="_active" href="" class="header-nav__choose-link">
          Для детей
        </NuxtLink>
      </div>
      <div class="header-nav__choose">
        <NuxtLink exact-active-class="_active" href="" class="header-nav__choose-link">
          Для взрослых
        </NuxtLink>
      </div>
      <div class="header-nav__choose">
        <NuxtLink exact-active-class="_active" href="" class="header-nav__choose-link">
          Праздники
        </NuxtLink>
      </div>
      <div class="header-nav__choose">
        <NuxtLink exact-active-class="_active" href="" class="header-nav__choose-link">
          Интересы
        </NuxtLink>
      </div>
      <div class="header-nav__choose">
        <NuxtLink exact-active-class="_active" href="" class="header-nav__choose-link">
          Контакты
        </NuxtLink>
      </div>
    </nav>
  </header>
</template>

<style scoped lang="scss">

.header {
  &-top {
    background: #F2F7FF;
    height: 80px;
    display: flex;
    align-items: center;

    &__search {
      width: 1313px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      gap: 162px;

      &-logo {
        width: 164px;
        height: 30px;
      }

      &-form {
        display: flex;
        align-items: center;
        gap: 10px;
        position: relative;

        svg {
          position: absolute;
          left: 12px;
          width: 24px;
          height: 24px;
        }
      }

      &-input {
        background: white;
        border: 1px solid #C5A7EB;
        border-radius: 40px;
        width: 540px;
        height: 48px;
        outline: none;
        padding-left: 45px;
        font: 400 17px/130% 'Montserrat';
        color: #1F074D;
        cursor: pointer;
      }

      &-button {
        width: 180px;
        height: 48px;
        background: #5C25C5;
        border-radius: 37px;
        font: 500 17px/130% 'Montserrat';
        color: white;
      }
    }
  }

  &-nav {
    height: 70px;
    width: 1313px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-bottom: 1px solid #A7BAEB;
  }

  &__choose {
    &-link {
      font: 400 19px/23px 'Montserrat';
      color: #1F074D;
    }
  }
}

</style>