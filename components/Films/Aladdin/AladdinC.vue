<template>
<b-card bg-variant="dark" text-variant="white" title= "Aladdin PG ">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/foyufD52aog"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
      Young Aladdin embarks on a magical adventure after finding a lamp that releases a wisecracking genie.
    </p>



<h4 class="title-color">Cineworld</h4>
<!--Bexleyheath-->
<b-button-group>
<Bexleyheathbutton />
</b-button-group>
<br><br>



<Friday />
<Saturday />
<Sunday />
<Monday />
<Tuesday />
<Wednesday />

<br><br>

<!--Greenwich-->
<b-button-group>
<Greenwichbutton />
</b-button-group>
<br><br>

<Friday />
<Saturday />
<Sunday />
<Monday />
<Tuesday />
<Wednesday />

<br><br>

<!--Ilford -->
<b-button-group>
<Ilfordbutton />
</b-button-group>
<br><br>


<Friday />
<Saturday />
<Sunday />
<Monday />
<Tuesday />
<Wednesday />

<br><br>

<!--west-->
<b-button-group>
<Westbutton />
  </b-button-group>

  <br><br>


<Friday />
<Saturday />
<Sunday />
<Monday />
<Tuesday />
<Wednesday />
<br><br>

  <h4 class="title-color">Odeon</h4>
  <!--Greenwich-->
  <b-button-group>
 <Ogreenwichbutton />
 </b-button-group>
  <br><br>


  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

<!--Southwoodford -->
 <b-button-group>
  <Osouthbutton />
  </b-button-group>
  <br><br>


  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

  <h4 class="title-color">Picturehouses</h4>
  <!--Greenwich -->
  <b-button-group>
  <Pgreenwichbutton />
  </b-button-group>
<br><br>



  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

<!--Hackney -->
  <b-button-group>
  <Phackneybutton />
  </b-button-group>

<br><br>


  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

<!--stratford-->
  <b-button-group>
  <Pstratfordbutton />
  </b-button-group>
  <br><br>


  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

  <h4 class="title-color">Showcase</h4>
  <!--Newham-->
  <b-button-group>
  <Newhambutton />
  </b-button-group>
  <br><br>


  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

  <h4 class="title-color">Vue</h4>
  <!--Romford -->
  <b-button-group>
  <Romfordbutton />
  </b-button-group>
  <br><br>


  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

  <!--Stratford -->
<b-button-group>
  <Vstratford />
  </b-button-group>
  <br><br>

  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

  <h4 class="title-color"></h4>
  <b-button-group>
    <AladdinR />
    <AladdinF />
    <Nineteen />
  </b-button-group>

</b-card>
</template>

<script>
import Bexleyheathbutton from '@/components/Cineworld/Bexleyheathbutton'
import Greenwichbutton from '@/components/Cineworld/Greenwichbutton'
import Ilfordbutton from '@/components/Cineworld/Ilfordbutton'
import Westbutton from '@/components/Cineworld/Westbutton'
import Ogreenwichbutton from '@/components/Odeon/Ogreenwichbutton'
import Osouthbutton from '@/components/Odeon/Osouthbutton'
import Pgreenwichbutton from '@/components/Picturehouses/Pgreenwichbutton'
import Phackneybutton from '@/components/Picturehouses/Phackneybutton'
import Pstratfordbutton from '@/components/Picturehouses/Pstratfordbutton'
import Newhambutton from '@/components/Showcase/Newhambutton'
import Romfordbutton from '@/components/Cinevue/Romfordbutton'
import Vstratford from '@/components/Cinevue/Vstratford'
import AladdinR from '@/components/Films/Aladdin/AladdinR'
import AladdinF from '@/components/Films/Aladdin/AladdinF'
import Nineteen from '@/components/Films/Year/Nineteen'
import Monday from '@/components/Films/Days/Monday'
import Tuesday from '@/components/Films/Days/Tuesday'
import Wednesday from '@/components/Films/Days/Wednesday'
import Thursday from '@/components/Films/Days/Thursday'
import Friday from '@/components/Films/Days/Friday'
import Saturday from '@/components/Films/Days/Saturday'
import Sunday from '@/components/Films/Days/Sunday'





export default {
  components: {
    Bexleyheathbutton,
    Greenwichbutton,
    Ilfordbutton,
    Westbutton,
    Ogreenwichbutton,
    Osouthbutton,
    Pgreenwichbutton,
    Phackneybutton,
    Pstratfordbutton,
    Newhambutton,
    Romfordbutton,
    Vstratford,
    AladdinR,
    AladdinF,
    Nineteen,
    Monday,
    Tuesday,
    Wednesday,
    Thursday,
    Friday,
    Saturday,
    Sunday,

      }
}
</script>



