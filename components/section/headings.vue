<script setup lang="ts">

interface IHeading {
  id: number
  img: string
  name: string,
  link: string
}

const headings: IHeading[] = [

  {
    id: 1,
    img: "/img/headings.png",
    name: " Мультфильмы",
    link: 'cartoon'
  },
  {
    id: 2,
    img: "/img/headings.png",
    name: " Мультфильмы",
    link: 'cartoon'
  },
  {
    id: 3,
    img: "/img/headings.png",
    name: " Мультфильмы",
    link: 'cartoon'
  },
  {
    id: 4,
    img: "/img/headings.png",
    name: " Мультфильмы",
    link: 'cartoon'
  },
]

defineProps<{
  headingsTitle:string
}>()

</script>

<template>
  <section class="headings section-headings">
    <div class="section-container">
      <h2 class="headings-title">
        {{headingsTitle}}
      </h2>
      <div class="headings-categories">
        <h3 class="headings-subtitle">
          Для детей
        </h3>
        <div class="headings-categories__wrapper">
          <NuxtLink class="headings-categories__wrapper-item"
                    v-for="heading in headings" :key="heading.id" :to="heading.link"
          >
            <p class="headings-categories__wrapper-name">
              {{ heading.name }}
            </p>
            <NuxtImg :src="heading.img" alt="img"/>
          </NuxtLink>
        </div>
        <NuxtLink to="" class="articles-transition">
          Все рубрики
        </NuxtLink>
      </div>
    </div>
  </section>
</template>

<style lang="scss">
.headings {
  padding-bottom: 20px;

  &-title {
    font: 700 48px/59px 'Montserrat';
    text-transform: uppercase;
    color: #5c25c5;
    padding-bottom: 40px;
  }

  &-subtitle {
    font: 500 36px/44px 'Inter';
    color: #5c25c5;
    padding-bottom: 20px;
  }

  &-categories {

    &__wrapper {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      grid-gap: 10px;
      padding-bottom: 40px;

      &-item {
        padding: 20px;
        width: 100%;
        min-height: 245px;
        background: #F6F2FF;
        border-radius: 40px;
        position: relative;
        bottom: -3px;
        transition: 0.5s all;
        cursor: pointer;
        &:hover{

          border: 1px solid #5c25c5;
          box-shadow: 0 0 4px 1px #817496;
          bottom: 0;
        }

        img {
          width: 100%;
        }
      }

      &-name {
        font: 500 19px/23px 'Montserrat';
        text-align: center;
        color: #1F074D;
        padding-bottom: 12px;
      }
    }
  }


}

</style>