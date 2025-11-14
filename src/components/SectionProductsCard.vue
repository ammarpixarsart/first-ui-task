<template>
  <div class="card border-0">
    <div class="row">
      <div class="col-md-4">
        <img :src="imgUrl" height="110" width="100%" style="object-fit: fill;"/>
      </div>
      <div class="col-md-8">
        <div class="card-body secondColumn">
          <p class="card-text">{{ title }}</p>
              <div class="card-text">
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
            </div>  
          <p class="fw-bold card-text">$ {{ price }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  imgUrl: String,
  title: String,
  price: Number
})
</script>

<style scoped>
.secondColumn{
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
}
.checked{
    color: yellow;
}
</style>
