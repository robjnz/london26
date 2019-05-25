<template>
<b-card bg-variant="dark" text-variant="white" title= "">
<h4 class="title-color"></h4>

  <b-button-group>
 <Ogreenwichbutton /><!--Greenwich-->
 </b-button-group>
  <br><br>


  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

  
 <b-button-group>
  <Osouthbutton /><!--Southwoodford -->
  </b-button-group>
  <br><br>


  <Friday />
  <Saturday />
  <Sunday />
  <Monday />
  <Tuesday />
  <Wednesday />
  <br><br>

</b-card>
</template>
<script>

import Ogreenwichbutton from '@/components/Odeon/Ogreenwichbutton'
import Osouthbutton from '@/components/Odeon/Osouthbutton'
import Monday from '@/components/Films/Days/Monday'
import Tuesday from '@/components/Films/Days/Tuesday'
import Wednesday from '@/components/Films/Days/Wednesday'
import Thursday from '@/components/Films/Days/Thursday'
import Friday from '@/components/Films/Days/Friday'
import Saturday from '@/components/Films/Days/Saturday'
import Sunday from '@/components/Films/Days/Sunday'






export default {
  components: {
    Ogreenwichbutton,
    Osouthbutton,
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





