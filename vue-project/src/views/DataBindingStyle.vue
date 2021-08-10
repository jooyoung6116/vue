<template>
  <div v-bind:style="styleObject">스타일 인바딩</div>
</template>
<script>
export default {
  data() {
    return {
      styleObject : 'color:red;fontSize:13px;'
    }
  }
}
</script>