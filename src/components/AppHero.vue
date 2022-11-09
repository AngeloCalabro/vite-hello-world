<template>
       <img :src="getImagePath(`../assets/img/${image}`)" alt="immagine">
        <TitleHero/>
</template>
  
<script>
import TitleHero from './TitleHero.vue';
    export default {
        components:{
        TitleHero
        },
        name: 'AppHero',
        data(){
            return{
                image : 'fswd.png'
            }
        },
        methods :{
            getImagePath: function(imgPath){
                return new URL (imgPath, import.meta.url).href;
            }
        }
    }
</script>
  
<style lang="css" scoped>

img{
    object-fit: cover;
    object-position: center;
    width: 80%;
    height: 50vw;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>