<script setup lang="ts">

</script>

<template>
  <div class="coloring-items">
    <div class="coloring-items__item">
      <NuxtImg class="coloring-items__item-img" width="276" src="/img/Img.png" alt="img"/>
      <p class="coloring-items__item-name">
        Милое авокадо
      </p>
    </div>
    <div class="coloring-items__item">
      <NuxtImg class="coloring-items__item-img" width="276" src="/img/Img2.png" alt="img"/>
      <p class="coloring-items__item-name">
        Морская птица Альбатрос летит
      </p>
    </div>
    <div class="coloring-items__item">
      <NuxtImg class="coloring-items__item-img" width="276" src="/img/Img.png" alt="img"/>
      <p class="coloring-items__item-name">
        Милое авокадо
      </p>
    </div>
    <div class="coloring-items__item">
      <NuxtImg class="coloring-items__item-img" width="276" src="/img/Img2.png" alt="img"/>
      <p class="coloring-items__item-name">
        Морская птица Альбатрос летит
      </p>
    </div>
    <div class="coloring-items__item">
      <NuxtImg class="coloring-items__item-img" width="276" src="/img/Img.png" alt="img"/>
      <p class="coloring-items__item-name">
        Милое авокадо
      </p>
    </div>
    <div class="coloring-items__item">
      <NuxtImg class="coloring-items__item-img" width="276" src="/img/Img2.png" alt="img"/>
      <p class="coloring-items__item-name">
        Морская птица Альбатрос летит
      </p>
    </div>
    <div class="coloring-items__item">
      <NuxtImg class="coloring-items__item-img" width="276" src="/img/Img.png" alt="img"/>
      <p class="coloring-items__item-name">
        Милое авокадо
      </p>
    </div>
    <div class="coloring-items__item">
      <NuxtImg class="coloring-items__item-img" width="276" src="/img/Img2.png" alt="img"/>
      <p class="coloring-items__item-name">
        Морская птица Альбатрос летит
      </p>
    </div>
  </div>
</template>

<style scoped lang="scss">
.coloring {

  &-items {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;

    &__item {
      border: 1px solid #c5a7eb;
      border-radius: 33px;
      padding: 20px 22px 0;
      position: relative;
      min-height: 360px;
      cursor: pointer;
      bottom: -3px;
      transition: 0.5s all;

      &:hover {
        border: 2px solid #5c25c5;
        box-shadow: 0 0 7px #5c25c5;
        bottom: 0;
      }

      &-img {
        margin-bottom: 8px;
      }

      &-name {
        font: 400 19px/23px 'Montserrat';
        line-height: 23px;
        text-align: center;
        color: #1f074d;
        padding-bottom: 8px;
        position: absolute;
        bottom: 8px;
        width: -webkit-fill-available;
      }
    }
  }
}
</style>