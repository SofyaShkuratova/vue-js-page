<template>
  <NavBar />
  <div id="app">
    <header>
    </header>
    <main>

      <div class="content">
        <AboutSection msg="Добро пожаловать"/>
      </div>
    </main>
  </div>
  <h1 class="text-center mb-1"> Каталог товаров </h1>
  <catalog-page />

  <div class="card m-5">
    <div class="card-header">
      Цитата
    </div>
    <div class="card-body">
      <blockquote class="blockquote mb-0">
        <p>Здоровье не всё, но все без здоровья - ничто</p>
        <footer class="blockquote-footer"><cite title="Source Title">Сократ</cite></footer>
      </blockquote>
    </div>
  </div>
  <catalog-page />

  <h1 class="text-center mt-5"> Оставьте отзыв о нашем магазине </h1>
  <form-cont />
  <foot-bar />
</template>

<script>
import AboutSection from "@/components/About.vue";
import NavBar from "@/components/NavBar.vue";
import CatalogPage from "@/components/CatalogPage.vue";
import FormCont from "@/components/FormCont.vue";
import FootBar from "@/components/FootBar.vue";


export default {
  name: 'App',
  components: {
    FootBar,
    FormCont,
    CatalogPage,
    NavBar,
    AboutSection,
  },
  msg: String
}
</script>

<style>

</style>
