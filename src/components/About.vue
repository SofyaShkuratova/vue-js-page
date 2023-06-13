<script>
export default {
  name: 'AboutSection',
  props: {
    msg: String
  }
}
</script>

<template>
  <div class="p-5 m-4 bg-body-tertiary rounded-3">
    <div class="container-fluid py-5">
      <h1 class="display-5 fw-bold">{{msg}} в наш магазин!</h1>
      <p class="col-md-8 fs-4">
        <strong>Vegan Store</strong> - магазин товаров и продуктов для веганов
      </p>
      <p class="alert-info">
        Разработка: Шкуратова Софья
      </p>
    </div>
  </div>
</template>

<style scoped>

</style>