<template>
    <h1>{{title}}</h1>
</template>
  
<script>
    export default {
        name: 'TitlePage',
        data(){
            return{
                title : "La mia prima app con Vite!"
            }
        }
    }
</script>

  
<style lang="css" scoped>
  h1{
    text-align: center;
    color: #0f0559;
    text-shadow: 5px 5px 8px #9b31f7;
    margin-bottom: 20px;
  }
</style>