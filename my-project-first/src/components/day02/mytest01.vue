<template>
    <div id="app">
        {{reventFun}}
    </div>
</template>
<script>
export default{
name:'test',
 el:'#app',
 data:  {
     text:'123,456'
 },
 methods:{
rreventFun:function(){
    return this.text.split(',').reverse().join()
}
 }    
}
</script>

