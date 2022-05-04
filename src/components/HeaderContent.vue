<template>
  <nav>
    <img class="logo" src="../assets/images/dc-logo.png" alt="">

    <ul>
        <li>Caracters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>Tv</li>
        <li>Games</li>
        <li>collectibles</li>
        <li>Videos</li>
        <li>Fans</li>
        <li>News</li>
        <li>Shop</li>
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
  color:#03a1fc ;
}

</style>
