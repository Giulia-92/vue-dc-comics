<template>
    <div>{{name}} -
        {{img}}
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
