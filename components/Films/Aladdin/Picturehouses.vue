<template>
<b-card bg-variant="dark" text-variant="white" title= "">
<h4 class="title-color"></h4>


  <b-button-group>
  <Pgreenwichbutton /><!--Greenwich -->
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
  <Phackneybutton /><!--Hackney -->
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
  <Pstratfordbutton /><!--stratford-->
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

import Pgreenwichbutton from '@/components/Picturehouses/Pgreenwichbutton'
import Phackneybutton from '@/components/Picturehouses/Phackneybutton'
import Pstratfordbutton from '@/components/Picturehouses/Pstratfordbutton'
import Monday from '@/components/Films/Days/Monday'
import Tuesday from '@/components/Films/Days/Tuesday'
import Wednesday from '@/components/Films/Days/Wednesday'
import Thursday from '@/components/Films/Days/Thursday'
import Friday from '@/components/Films/Days/Friday'
import Saturday from '@/components/Films/Days/Saturday'
import Sunday from '@/components/Films/Days/Sunday'






export default {
  components: {
    Pgreenwichbutton,
    Phackneybutton,
    Pstratfordbutton,
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





