<template>
  <div>
    <router-link class="grosBoutonVert"  :to="route"> {{message}} </router-link>
  </div>'
</template>

<style>
.grosBoutonVert{
  width: 80%;
  height: 100px;
  color: white;
  font-size: 20px;
  background-color: rgb(66, 200, 60);
  padding: 5% 25%;
  border-radius: 25px;
  text-decoration: none;
}
</style>

<script>
export default {
  props: ['message',
          'route']
}
</script>