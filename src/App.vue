<script setup>

</script>

<template>
 <div class="container">
   <div class="row">
      <div class="col">
        <h1 class="text-center mt-4">Учет товаров</h1>
        <form action="">
          <div class="mb-3">
            <label for="name" class="form-label">Название товара</label>
            <input type="text" class="form-control" id="name">
            </div>
            <div class="mb-3">
            <label for="date" class="form-label">Дата добавления</label>
            <input type="date" class="form-control" id="date">
            </div>
            <div class="mb-3">
            <label for="count" class="form-label">Количество</label>
            <input type="number" class="form-control" id="count">
            </div>
            <div class="mb-3">
            <label for="price" class="form-label">Цена</label>
            <input type="number" class="form-control" id="price">
            </div>

            <div class="mb-3 text-center">
              <button type="button" class="btn btn-outline-danger">Добавить</button>
            </div>

        </form>
      </div>
    </div>



    <div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Samsung</h5>
        <p class="card-text">25.11.2024</p>
        <p class="card-text">$500</p>
        <p class="card-text">x5</p>
      </div>
      <div class="card-footer text-end">
        <button class="btn btn-outline-danger">Удалить</button>
      </div>
    </div>
  </div>
  </div>



 </div>
</template>

