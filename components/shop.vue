<template>
  <div class="flex bg-blue-100 w-18 p-4 rounded-full">
      <img class="h-8 w-8" src="https://image.flaticon.com/icons/png/128/726/726566.png" alt="">
      <h1>{{count}}</h1>
  </div>
</template>

<script>
export default {
    props:{
        count:{
            default:0
        }
    }

}
</script>

<style>

</style>