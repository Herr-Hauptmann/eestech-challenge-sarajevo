<script setup>
import { RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
</script>

<template>
  <Navbar />
  <RouterView />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');



.bg-eestech-1{
  background-color: #113b60;
}
.bg-eestech-2{
  background-color: #036cad;
}
.bg-eestech-3{
  background-color: #0e83d7;
}
.bg-eestech-4{
  background-color: #52bde9;
}
.text-eestech-1{
  color: #113b60;
}
.text-eestech-2{
  color: #036cad;
}
.text-eestech-3{
  color: #0e83d7;
}
.text-eestech-4{
  color: #52bde9;
}
.roboto{
  font-family: 'Roboto', sans-serif;
}
</style>
