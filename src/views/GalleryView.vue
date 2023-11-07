<template>
  <div class="container-fluid">
    <div class="container">
    <h1 class="text-center">Bakery Price List</h1>
    <div class="row price-list">
      <div class="col-md-4">
        <div class="price-item">
          <h3>Chocolate Chip Cookies</h3>
          <p>Price: $2.50 per piece</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="price-item">
          <h3>Cupcakes</h3>
          <p>Price: $3.00 each</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="price-item">
          <h3>Fruit Tarts</h3>
          <p>Price: $4.50 each</p>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
</script>

<style scoped>
 .price-list {
      margin-top: 20px;
    }
    .price-item {
      border: 1px solid #ccc;
      padding: 10px;
      margin-bottom: 10px;
      border-radius: 5px;
      background-color: #f9f9f9;
    }
</style>
