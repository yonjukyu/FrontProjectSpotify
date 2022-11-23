<script>
export default {
  props: ['message']
}
</script>

<template>
    <textarea class="textArea" :value = "message"></textarea>
</template>

<style>
.textArea{
  width: 90%;
  height: 70px;
  color: rgba(255,255,255,0.7);
  text-align:center;
  display: block;
  margin-left: auto;
  margin-right: auto;
  font-size: 20px;
  background-color: rgba(0,0,0,0);
  border-radius: 30px;
  margin-top: 20px;
}
</style>


