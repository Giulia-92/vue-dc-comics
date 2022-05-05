<template>
    <div>{{name}} -
        {{type}} -
        {{img}} -
        {{price}}
    </div>
   
</template>
<script>
export default {
  name: 'PicturesContent',
  props:{
      name:String,
      type:String,
      img:Object,
      price:Number,
  }
}
</script>
