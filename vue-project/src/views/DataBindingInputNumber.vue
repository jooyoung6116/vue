<template>
  <div>
    <input type='number' v-model.number='numberModel'>
    <input type='number' v-model.number='numberModel2'>
  </div>
</template>
<script>
export default {
  data() {
    return {
      numberModel : 3,
      numberModel2 : 4
    };
  }
}
</script>
