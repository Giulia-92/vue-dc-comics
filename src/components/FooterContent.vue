<template>
  <section class="comicbook">
     
    <div class="logobg">
<ul class="info">
        <li>DC COMICS</li>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>

    </ul>
  <img src="../assets/images/dc-logo-bg.png" alt="">
  </div>
    <section class="footer" >
        <button class="btn">SIGN-UP NOW!</button>
        <h4>FOLLOW US</h4>
        <ul class="sponsor">
            <li><img src="../assets/images/footer-twitter.png" alt="" > </li>
            <li><img src="../assets/images/footer-periscope.png" alt="" > </li>
            <li><img src="../assets/images/footer-pinterest.png" alt="" > </li>
            <li><img src="../assets/images/footer-facebook.png" alt="" > </li>
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
    margin-top:40px;
    margin-left:50%;
   
}
.comicbook{
background-image: url('../assets/images/footer-bg.jpg');
background-repeat: repeat;
position: relative;
height:600px;
}
.logobg{
 position: absolute;
margin-top:1%;
margin-left: 50%;
}

ul .info{
    color:white;

}    

.footer{
    background-color:#272829;
    width:100%;
    height:110px;
    margin-top:-40px;
    display:flex;
    margin-top:30%;
    position: absolute;
    justify-content: flex-end;  
}
.btn{
    background-color: #272829;
    border: 3px solid #0c75d7;
    width: 150px;
    height:60px;
    color: white;
    font-size:20px;
    font-family:'Roboto Condensed', sans-serif;
    display: flex;
    align-items: center;
    margin-top:20px;
    padding-left:12px;
    
   
}
.sponsor{ 
    display: flex;
    margin-left:30px;
    align-items:flex-end;
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
