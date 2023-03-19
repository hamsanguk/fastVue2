<template>
  <div>
    <HelloWorld />
    <h1>{{ message }}</h1>
  </div>  
</template>

<script>
import HelloWorld from '~/components/HelloWorld.vue'

export default{
    components:{
        HelloWorld
    },
    data(){
        return{
            message:'hello vue'
        }
    }
}
</script>