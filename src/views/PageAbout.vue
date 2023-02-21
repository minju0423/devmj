<template>
  <div class="about">
    <button type="button" v-on:click="onClickRedirect">Google</button>
  </div>
</template>

<script>
export default {
  methods : {
    onClickRedirect: function () {   
      window.open("https://www.google.co.kr/", "_blank");    
      
    }
  }
  
}
</script>

<style scoped>

</style>