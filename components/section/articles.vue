<script setup lang="ts">

defineProps<{
  articlesTitle: string
}>()

</script>

<template>
  <section class="articles section-articles">
    <div class="section-container">
      <h2 class="section-title">
        {{ articlesTitle }}
      </h2>
      <div class="articles-items">
        <div class="articles-items__item">
          <NuxtLink to="" class="articles-items__item-link">
            <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M6.45862 1.09925C6.75762 0.800251 7.24238 0.800251 7.54138 1.09925L12.9008 6.45862C13.1997 6.75762 13.1997 7.24238 12.9008 7.54138L7.54138 12.9008C7.24238 13.1997 6.75762 13.1997 6.45862 12.9008C6.15963 12.6018 6.15963 12.117 6.45862 11.818L10.511 7.76562H1.64062C1.21778 7.76562 0.875 7.42284 0.875 7C0.875 6.57716 1.21778 6.23437 1.64062 6.23437H10.511L6.45862 2.182C6.15963 1.88301 6.15963 1.39824 6.45862 1.09925Z"
                    fill="#1F074D"/>
            </svg>
          </NuxtLink>
          <NuxtImg class="articles-items__item-img" width="430" height="240" src="/img/articles.png" alt="img"/>
          <h4 class="articles-items__item-name">
            «Три Богатыря и Пуп Земли» стал самым успешным российским мультфильмом в истории
          </h4>
          <p class="articles-items__item-text">
            Уникальное путешествие по реке ОКАВАНГО, перемещение на оснощённых спец.катерах, проживание в пятизвйздочных
            палатках, весь путь в сопровождении русско-говорящего гида.
          </p>
        </div>
        <div class="articles-items__item">
          <NuxtLink to="" class="articles-items__item-link">
            <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M6.45862 1.09925C6.75762 0.800251 7.24238 0.800251 7.54138 1.09925L12.9008 6.45862C13.1997 6.75762 13.1997 7.24238 12.9008 7.54138L7.54138 12.9008C7.24238 13.1997 6.75762 13.1997 6.45862 12.9008C6.15963 12.6018 6.15963 12.117 6.45862 11.818L10.511 7.76562H1.64062C1.21778 7.76562 0.875 7.42284 0.875 7C0.875 6.57716 1.21778 6.23437 1.64062 6.23437H10.511L6.45862 2.182C6.15963 1.88301 6.15963 1.39824 6.45862 1.09925Z"
                    fill="#1F074D"/>
            </svg>
          </NuxtLink>
          <NuxtImg class="articles-items__item-img" width="430" height="240" src="/img/articles.png" alt="img"/>
          <h4 class="articles-items__item-name">
            «Три Богатыря и Пуп Земли» стал самым успешным российским мультфильмом в истории
          </h4>
          <p class="articles-items__item-text">
            Уникальное путешествие по реке ОКАВАНГО, перемещение на оснощённых спец.катерах, проживание в пятизвйздочных
            палатках, весь путь в сопровождении русско-говорящего гида.
          </p>
        </div>
        <div class="articles-items__item">
          <NuxtLink to="" class="articles-items__item-link">
            <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M6.45862 1.09925C6.75762 0.800251 7.24238 0.800251 7.54138 1.09925L12.9008 6.45862C13.1997 6.75762 13.1997 7.24238 12.9008 7.54138L7.54138 12.9008C7.24238 13.1997 6.75762 13.1997 6.45862 12.9008C6.15963 12.6018 6.15963 12.117 6.45862 11.818L10.511 7.76562H1.64062C1.21778 7.76562 0.875 7.42284 0.875 7C0.875 6.57716 1.21778 6.23437 1.64062 6.23437H10.511L6.45862 2.182C6.15963 1.88301 6.15963 1.39824 6.45862 1.09925Z"
                    fill="#1F074D"/>
            </svg>
          </NuxtLink>
          <NuxtImg class="articles-items__item-img" width="430" height="240" src="/img/articles.png" alt="img"/>
          <h4 class="articles-items__item-name">
            «Три Богатыря и Пуп Земли» стал самым успешным российским мультфильмом в истории
          </h4>
          <p class="articles-items__item-text">
            Уникальное путешествие по реке ОКАВАНГО, перемещение на оснощённых спец.катерах, проживание в пятизвйздочных
            палатках, весь путь в сопровождении русско-говорящего гида.
          </p>
        </div>
        <div class="articles-items__item">
          <NuxtLink to="" class="articles-items__item-link">
            <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M6.45862 1.09925C6.75762 0.800251 7.24238 0.800251 7.54138 1.09925L12.9008 6.45862C13.1997 6.75762 13.1997 7.24238 12.9008 7.54138L7.54138 12.9008C7.24238 13.1997 6.75762 13.1997 6.45862 12.9008C6.15963 12.6018 6.15963 12.117 6.45862 11.818L10.511 7.76562H1.64062C1.21778 7.76562 0.875 7.42284 0.875 7C0.875 6.57716 1.21778 6.23437 1.64062 6.23437H10.511L6.45862 2.182C6.15963 1.88301 6.15963 1.39824 6.45862 1.09925Z"
                    fill="#1F074D"/>
            </svg>
          </NuxtLink>
          <NuxtImg class="articles-items__item-img" width="430" height="240" src="/img/articles.png" alt="img"/>
          <h4 class="articles-items__item-name">
            «Три Богатыря и Пуп Земли» стал самым успешным российским мультфильмом в истории
          </h4>
          <p class="articles-items__item-text">
            Уникальное путешествие по реке ОКАВАНГО, перемещение на оснощённых спец.катерах, проживание в пятизвйздочных
            палатках, весь путь в сопровождении русско-говорящего гида.
          </p>
        </div>
      </div>
      <NuxtLink to="" class="articles-transition">
        Перейти в блог
      </NuxtLink>
    </div>
  </section>
</template>

<style lang="scss">

.articles {

  &-items {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    padding-bottom: 16px;

    &__item {
      position: relative;
      border-radius: 40px;
      transition: 0.5s all;

      &:hover {
        box-shadow: 1px 2px 4px -1px #817496;

      }

      &-img {
        margin-bottom: 22px;
      }

      &-name {
        font: 500 20px/24px 'Montserrat';
        color: #1f074d;
        padding: 0 12px 8px;
      }

      &-text {
        font: 400 17px/21px 'Montserrat';
        color: #1f074d;
        padding: 0 12px 37px;
      }

      &-link {
        position: absolute;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 34px;
        height: 36px;
        background: white;
        border-radius: 12px;
        top: 20px;
        right: 28px;

        &:hover {
          background: #5c25c5;
          border-radius: 12px;
          transition: 0.5s all;

          path {
            fill: white;
          }
        }
      }
    }
  }

  &-transition {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 180px;
    height: 48px;
    background: #5C25C5;
    border-radius: 37px;
    margin: 0 auto;
    font: 500 17px/21px 'Montserrat';
    color: white;

  }
}

</style>