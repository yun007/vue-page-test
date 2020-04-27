<template>
  <div class="box">
    <h1>{{homeTitle}}</h1>
  </div>
</template>

<script>
export default {
  data(){
    return {
      homeTitle : "난 yun component"
    }
  }
}
</script>

<style scoped>
.box{border:solid 1px red}
</style>