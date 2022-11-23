<template>
  <div>
    <button class="grosBoutonVert" @click="$router.push('/')" > {{message}} </button>
  </div>
</template>

<style>
.grosBoutonVert{
  width: 80%;
  height: 100px;
  color: white;
  font-size: 25px;
  background-color: rgb(66, 200, 60);
  border: none;
  border-radius: 15px;
  margin-top: 20px;
}
</style>

<script>
export default {
  props: ['message',
          'route']
}
</script>