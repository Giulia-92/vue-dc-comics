<template>
  <nav>
    <img class="logo" src="../assets/images/dc-logo.png" alt="">

    <ul>
        <li> <a href="#">Caracters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">Tv</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Collectibles</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">Fans</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Shop</a></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'HeaderContent',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
.logo{
    height:70px;
    width:70px;
   float:left;
   margin-left:200px;
  margin-top:-25px;
}
nav
{
  height:50px;
  width: 120%;
  
}
ul {
  list-style-type: none;
  padding: 0;

}
li {
  display: inline-flex;
 justify-content: flex-end;
 flex-direction: row;
  margin: 0 10px;
  font-family:'Varela Round', sans-serif;
  color:#5b5d5e;
}
a {
  color:#5b5d5e; 
  text-decoration: none;
}

a:hover{
 text-decoration:underline#03a1fc 3px;
 color: #03a1fc;
}

</style>
