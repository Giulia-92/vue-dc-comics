<template>
  <main>
    <section class="black">
      Content goes here
    </section>
    <section class="blue">
       <ul>
        <li>
          <img class="card" src="../assets/images/buy-comics-digital-comics.png" alt="">
          <h3>DIGITAL COMICS</h3></li>
        <li><img class="card" src="../assets/images/buy-comics-merchandise.png" alt="" > <h3>DC MERCHANDISE</h3></li>
        <li><img class="card" src="../assets/images/buy-comics-shop-locator.png" alt="" > <h3>SUBSCRIPTION</h3></li>
        <li><img class="card" src="../assets/images/buy-comics-subscriptions.png" alt="" > <h3> COMIC SHOP LOCATOR</h3></li>
        <li><img class="card" src="../assets/images/buy-dc-power-visa.svg" alt="" > <h3>DC POWER VISA</h3></li>
        <li></li>
        
    </ul>
    </section>
    
  </main>
</template>

<script>
export default {
  name: 'MainContent',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
 color:white;
  font-family:'Roboto Condensed', sans-serif;
 margin-top:-30px; 

}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.black{
  background-color: black;
  color: white;
  font-family:'Roboto Condensed', sans-serif;
  height:150px;
  font-size: 50px;
  display: flex;
  justify-content: flex-start;
}
.blue{
  background-color:#008eed;
  display: inline-flex;
  width: 100%;
  height: 180px;
}
.card{
  width:50px;
  height:50px;
 margin-left:10px;
 margin-right:250px;
 margin-top:20px;
}
</style>
