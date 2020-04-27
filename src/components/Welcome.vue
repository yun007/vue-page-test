<template>
    <div class="group">    
        <h2>나는 Welcome component</h2>
        <p>{{hello}} 반갑습니다.</p>
    </div>
</template>

<script>
export default {
    data(){
        return{
            hello : '환영합니다.'
        }
    }
}
</script>

<style scoped>
    .group{
        background-color:#e2e2e2;
    }
    p{
        font-size:30px;
        color:000;
    }
</style>