<template>
    <div class='index'>
        <garden/>  
    </div>
</template>
<script>
import garden from '@/components/cursor/garden'
export default {
    components:{
        garden
    },
    data(){
        return {

        }
    },
    mounted(){
        alert('欢迎')
    }
}
</script>
<style lang="scss" scoped>
.index {
    width :100%;
    height :100%;
}
    


    
</style>

