<template>
  <div class="card shadow card-product">
    <img src="#img ke api" class="card-img-top" alt="..." />
    <div class="card-body">
      <h5 class="card-title"> {{ product.name }}</h5>
      <p
        class="card-text"
      >Harga : Rp. {{ product.harga }}</p>
      <router-link class="btn btn-success" to="#detailroduk"> Detail</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardProduct",
  props: ["product"],
};
</script>

<style>
</style>