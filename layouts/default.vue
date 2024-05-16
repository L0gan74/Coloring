<script setup lang="ts">

import Header from "~/layouts/header.vue";
import Footer from "~/layouts/footer.vue";
</script>

<template>
  <div class="wrapper">
    <Header/>
    <div class="container">
      <slot/>
      <button type="button" class="up-button">
        <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="30" cy="30" r="30" fill="#C5A7EB"/>
          <path d="M43.3799 36.1747C43.1976 36.357 42.9808 36.5017 42.7419 36.6004C42.503 36.6992 42.2468 36.75 41.988 36.75C41.7291 36.75 41.4729 36.6992 41.234 36.6004C40.9951 36.5017 40.7783 36.357 40.596 36.1747L31.6169 27.2678C31.4347 27.0855 31.2179 26.9408 30.979 26.8421C30.7401 26.7434 30.4838 26.6925 30.225 26.6925C29.9662 26.6925 29.7099 26.7434 29.471 26.8421C29.2321 26.9408 29.0153 27.0855 28.833 27.2678L19.854 36.1747C19.6717 36.357 19.4549 36.5017 19.216 36.6004C18.9771 36.6992 18.7209 36.75 18.462 36.75C18.2032 36.75 17.947 36.6992 17.7081 36.6004C17.4692 36.5017 17.2523 36.357 17.0701 36.1747C16.705 35.8104 16.5 35.3175 16.5 34.8037C16.5 34.2899 16.705 33.797 17.0701 33.4326L26.0688 24.5062C27.1715 23.4137 28.6664 22.8 30.225 22.8C31.7836 22.8 33.2785 23.4137 34.3812 24.5062L43.3799 33.4326C43.745 33.797 43.95 34.2899 43.95 34.8037C43.95 35.3175 43.745 35.8104 43.3799 36.1747Z" fill="white"/>
        </svg>
      </button>
    </div>
    <Footer/>
  </div>
</template>

<style scoped lang="scss">

.wrapper {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.container {
  flex: 1;
  padding: 41px 0 60px;
  position: relative;
}

.up-button{
  position: fixed;
  right: 40px;
  bottom: 152px;
}

</style>