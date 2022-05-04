<template>
<section class="comicbook">
    
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    
    <section class="footer" >
        <h4>FOLLOW US</h4>
        <ul>
            <li><img  src="../assets/images/footer-twitter.png" alt="" > </li>
            <li><img  src="../assets/images/footer-periscope.png" alt="" > </li>
            <li><img  src="../assets/images/footer-pinterest.png" alt="" > </li>
            <li><img  src="../assets/images/footer-facebook.png" alt="" > </li>
        </ul>
    </section>
  </section>
  
</template>

<script>
export default {
  name: 'FooterContent',
}
</script>
<style scoped lang="scss">
h4{
    color: #0c75d7;
    font-family:'Roboto Condensed', sans-serif;
    font-size:20px;
    padding-top:40px;
}
.comicbook{

}
.footer{
    background-color:#272829;
    width:100%;
    height:110px;
   
   
}

ul {
  list-style-type: none;
  padding: 0;
}
li{
   display: inline-flex;
   margin-top:-35px;
   margin-bottom:30px;
   margin-right:40px;
   
   float:right;
}

</style>
