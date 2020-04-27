<template>
  <div class="box">
    <h1>{{globalTitle}}</h1>
  </div>
</template>

<script>
export default {
  data(){
    return {
      globalTitle : "난 Global component"
    }
  }
}
</script>

<style scoped>
.box{border:solid 1px red}
</style>