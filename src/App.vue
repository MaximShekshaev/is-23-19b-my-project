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
 </div>
</template>

