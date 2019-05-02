<template>
<section main>
  <b-container>
    <h1 class="title-color">What on this month @ East London Theatres</h1>
    <h2>May 2019</h2>
    <br>
    <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "The Storm - James Wilton Dance">
  <p class="title-color">
    <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/Kq31sHs9cUo"
          allowfullscreen
  ></b-embed>

    Broadway Theatre Barking<br>
    Thurs 2 May 2019 7.30pm


    </p>

    <b-button href="https://kutt.it/barkingt" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Our House">
  <p class="title-color">
    Greenwich Theatre<br>
    Mon 29 April - Sat 4 May 2019
    </p>
    <b-button href="https://kutt.it/greenwichT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Laugh in the Face of Hate">
  <p class="title-color">
    Hackney Empire<br>
    Mon 29 April @ 7.30pm

    </p>
    <b-button href="https://kutt.it/hackneyT" target="_blank" variant="info">open</b-button>

</b-card>
    </b-card-group>

        <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Block Universe">
  <p class="title-color">
    Hoxton Hall<br>
    Thurs 30 May - Fri 31 May @ 7.30pm
    </p>
    <b-button href="https://kutt.it/hoxtonT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Rock 'n' Roll Paradise">

  <p class="title-color">
    Kenneth More Theatre Ilford<br>
    Fri 3 May 2019 @ 7.30 pm

</p>
    <b-button href="https://kutt.it/ilfordT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "The Hired Man">


  <p class="title-color">
    <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/UwPj9I7Jytg"
          allowfullscreen
  ></b-embed>
    Queen's Theatre Hornchurch<br>
    Sat 27 Apr - Sat 18 May 2019

    </p>
    <b-button href="https://kutt.it/queensT" target="_blank" variant="info">open</b-button>

</b-card>

    </b-card-group>

    <b-card-group deck
      class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Noughts & Crosses">
  <p class="title-color">
    Theatre Royal Stratford East<br>
    Wed 24 April - Sat 4 May 2019

    </p>
    <b-button href="https://kutt.it/stratfordeastT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Take That Greatest Hits Live">
  <p class="title-color">
    The O2 arena<br>
    Thurs 2 May - Fri 10 May 2019

    </p>
    <b-button href="https://kutt.it/Theo2T" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "The Crucible">
  <p class="title-color">

    The Yard Hackney<br>
    Wed 27 March — Thurs 11 May 2019

    </p>
    <b-button href="https://kutt.it/yardT" target="_blank" variant="info">open</b-button>

</b-card>


    </b-card-group>
      <div>
      <b-card-group deck
      class="mb-3">
    <b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">

  </p>
  <b-button-group>
  <b-button href="http://bit.ly/2O857LG" target="_blank" variant="info">Broadway Theatre Barking</b-button>
  <b-button href="http://bit.ly/2CKtih3" target="_blank" variant="info">Greenwich Theatre</b-button>
  <b-button href="http://bit.ly/2JnhX7Z" target="_blank" variant="info">Hackney Empire</b-button>
  </b-button-group>
  <br>
  <br>
  <b-button-group>
  <b-button href="http://bit.ly/2EX7IsG" target="_blank" variant="info">Hoxton Hall</b-button>
  <b-button href="http://bit.ly/2D9UPtc" target="_blank" variant="info">Kenneth More Theatre Ilford</b-button>
  <b-button href="http://bit.ly/2Soh3MB" target="_blank" variant="info">Queen's Theatre Hornchurch</b-button>
  </b-button-group>
  <br>
  <br>
  <b-button-group>
  <b-button href="http://bit.ly/2JjU3Kr" target="_blank" variant="info">Theatre Royal Stratford East</b-button>
  <b-button href="http://bit.ly/2PpXswU" target="_blank" variant="info">The 02</b-button>
  <b-button href="http://bit.ly/2OYFsdx" target="_blank" variant="info">The Yard Hackney</b-button>
  </b-button-group>

  </b-card>
  </b-card-group>

</div>

      </b-container>
      </section>

</template>

<script>
export default {
  head () {
    return {
      titleTemplate: '%s theatres',
      meta         : [
        { hid: 'description', name: 'description', content: 'Whats on at the east London Theatres this month, May 2019, Hackney empire, Kenneth More Theatre Ilford, Theatre Royal Stratford East and more!' }
      ]
    }
  }
}
</script>
