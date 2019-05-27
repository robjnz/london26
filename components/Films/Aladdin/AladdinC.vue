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

    <Today />
    
    <div>
    <b-button block variant="info" id="show-btn" @click="$bvModal.show('bv-modal-example')">Showing This Week</b-button>

    <b-modal class="film" id="bv-modal-example" hide-footer>
      <template slot="modal-title">
      
      </template>
      <div class="d-block text-center">
        <h3 class="asian">Aladdin</h3>
        <Today />
      </div>
      <b-button class="mt-3" block @click="$bvModal.hide('bv-modal-example')">Close Me</b-button>
    </b-modal>
  </div>


  <h4 class="title-color"></h4>
  <b-button-group>
    <AladdinR />
    <AladdinF />
    <Nineteen />
  </b-button-group>

</b-card>
</template>

<style>
.film{

  background: #343A40;
}

</style>

<script>




import AladdinR from '@/components/Films/Aladdin/AladdinR'
import AladdinF from '@/components/Films/Aladdin/AladdinF'
import Nineteen from '@/components/Films/Year/Nineteen'
import Today from '@/components/Films/Aladdin/Today'





export default {
  components: {
    AladdinR,
    AladdinF,
    Nineteen,
    Today,
      }
}
</script>



