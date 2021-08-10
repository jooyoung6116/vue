<template>
  <div>
      <select v-model="city">
          <option value="02">서울</option>
          <option value="031">인천</option>
          <option value="032">경기</option>
      </select>
  </div>       
</template>
<script>
  export default {
    data() {
      return {
        city:'032'
      };
    }
  }
</script>