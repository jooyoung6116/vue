<template>
  <SchoolTitle />
  <school-title />
  <div>
    <input type='text' v-model='valueModel' />
  </div> 
</template>
<script>
import SchoolTitle from "../components/SchoolTitle.vue";
export default {
  components : { SchoolTitle },
  data() {
    return{
      valueModel : 'South Korea'
    };
  }
}
</script>

