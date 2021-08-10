<template>
  <div v-bind:style="[base, add]">스타일 바인딩</div>
</template>
<script>
export default {
  data() {
    return {
      base : 'background-color:yellow;width:100%;height:200px;color:red;font-weight:bold;'
    }
  }
}
</script>