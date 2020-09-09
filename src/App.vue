<template>
  <div id="app">
    <HelloWorld msg=""/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
   data(){ 
          return{
            dataObject:{
              url: require('./assets/logo.png'), 
              title: 'Title'
             }
            }
          },
  
  components: {
    HelloWorld
  }
  
  
}
</script>

