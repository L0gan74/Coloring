<script setup lang="ts">

import ColoringItem from "~/components/item/coloring-item.vue";

defineProps<{
  pageTitle?: string,
  categoryTitle: string,
  colorCategoryTitle?: string,
  sectionName?: string,
}>()

type CategoriesFilter = {
  id: number,
  name: string
}

const categoriesKids: CategoriesFilter[] = [
  {id: 1, name: "Мультфильмы"},
  {id: 2, name: "Видеоигры"},
  {id: 3, name: "Животные"},
  {id: 4, name: "Природа"},
  {id: 5, name: "Все"},
]

</script>

<template>
  <section class="categories" :class="sectionName">
    <div class="section-container">
      <h1 class="categories-title">
        {{ pageTitle }}
      </h1>
      <div class="categories-which">
        <h2 class="categories-name" :class="colorCategoryTitle">
          {{ categoryTitle }}
        </h2>
        <div class="categories-tags">
          <button type="button">
            Мультфильмы
          </button>
          <button type="button">
            Мультфильмы
          </button>
          <button type="button">
            Мультфильмы
          </button>
          <button type="button">
            Мультфильмы
          </button>
        </div>
      </div>
      <ColoringItem/>
    </div>
  </section>
</template>

<style lang="scss">

.categories {
  &-title {
    font: 700 48px/59px 'Montserrat';
    text-transform: uppercase;
    color: #5C25C5;
    padding-bottom: 30px;
  }

  &-which {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 30px;
  }

  &-name {
    font: 500 36px/44px 'Inter';
    color: #5C25C5;

    &.green {
      color: #136C31;
    }
    &.blue {
      color: #2552C5;
    }
  }

  &-tags {
    display: flex;
    gap: 16px;

    button {
      padding: 0 17px;
      height: 38px;
      border: 1px solid #5C25C5;
      border-radius: 16px;
      font: 400 17px/130% 'Montserrat';
      color: #1F074D;
      transition: 0.5s all;

      &:hover {
        background: #5C25C5;
        box-shadow: 1px 2px 4px -1px #817496;
        color: #F6F2FF;
      }
    }
  }
}

</style>