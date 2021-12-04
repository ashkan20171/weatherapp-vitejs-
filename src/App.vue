<template>
<div class="d-flex justify-content-center">
<div class="card" style="width: 18rem;">
  <img src="./assets/city.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <div class="input-group mb-3">
  <button class="btn btn-primary" type="button" @click="getData" id="button-addon1">ارسال</button>
  <input type="text" class="form-control" placeholder="اسم شهر را وارد کنید" aria-label="Example text with button addon" aria-describedby="button-addon1">
     </div>
    <p class="card-text"></p>
  </div>
</div>
</div>
</template>

<script>
const API_KEY = 'ec0df541ed9c9cd210bb42bd99cf4a1e';

export default {
name: "App",

data: () => ({

}),

methods: {
 getData() {
 
 } 
}

}
</script>

<style>
</style>
