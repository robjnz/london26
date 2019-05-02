<template>
<section show class="showcase">
  <div class="intro" >

      <br><br>
    <b-badge pill variant="dark">
    <h1> <font color="gold"><br>Thursday<br>2nd May 2019</font></h1>
    <h2> What’s on today @ <br>the local cinemas,<br> theatres & nightclubs, <br>football matches & <br>places to visit <br>for days out <br>in east London.
</h2>
<!--
<h3 class="title-color">

  Home Game<br><b-img src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_30,w_30/v1544943996/leyton_orient_wltsdq.jpg" alt="leyton orient F.C."/>
Leyton Orient F.C.<br>V<br>Braintree Town<br> @ 12.30pm
<br>
<b-button href="https://kutt.it/orient-fc" target="_blank" variant="info">open</b-button>
</h3>
-->
<h3 class ="tory">
<br>Red Joan<br>

<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/gkecgBW-Y80"
          allowfullscreen
  ></b-embed>
    Showing today @
  <br>Vue

<br>
Statford

</h3>

<b-button href="https://kutt.it/vue-stratford" target="_blank" variant="info">open</b-button>
<br>
<br>

<h3 class="labour"> The Storm - James Wilton Dance<br>

<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/Kq31sHs9cUo"
          allowfullscreen
  ></b-embed>

    Showing today @
  <br> Broadway Theatre Barking
  <br>@<br>7.30pm
</h3>
<b-button href="https://kutt.it/barkingt" target="_blank" variant="info">open</b-button>
<br><br>

    </b-badge>

    </div>


  </section>
</template>
<style scoped>
.showcase{
  background             : url(http://res.cloudinary.com/dzhbfdfa5/image/upload/v1515831480/tower_vow6im.jpg) no-repeat center center fixed;
  background-size        : cover;
  -webkit-background-size: cover;
  -moz-background-size   : cover;
  -o-background-size     : cover;
  height                 : 1500px;
  margin-top             : -75px;

}
.intro{
  margin-left : 20px;
  margin-right: 900px;
  margin-top  : 50px;
  padding-left: 30px;
  color       : ghostwhite;
  font-family : Damion;
  }

  .alert{
  margin-left : 20px;
  margin-right: 1000px;
  margin-top  : 1px;
  padding-left: 30px;
  color       : #171718;
  font-family : Damion;
  }




</style>

<script>


export default {

  components: {

}
}
</script>
