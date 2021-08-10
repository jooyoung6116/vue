<template>
  <div>
    <input type="radio" v-bind:value="radioValue1" v-model="t">서울 
    <input type="radio" v-bind:value="radioValue2" v-model="t">부산 
    <input type="radio" v-bind:value="radioValue3" v-model="t">인천 
    <br>
    <span>선택지역 : {{ t }}</span>
  </div>
</template>
<script>
export default {
 data() {
   return {
     t : '',
     radioValue1 : '서울',
     radioValue2 : '부산',
     radioValue3 : '인천',
  };
 }
}
</script>