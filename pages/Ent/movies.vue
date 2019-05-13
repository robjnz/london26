
<template>
<section>
  <b-container>
    <h1 class="title-color">Movies showing today @ east London cinemas </h1>
    <br>
    <h2>Tuesday 14th May 2019</h2>

    <b-card-group deck
    class="mb-3">
    <DogC /><!--A Dog's Way Home-->
    <GraceC /><!--Amazing Grace-->
    <AvengersC /><!--Avengers Endgame -->
    </b-card-group>

    <b-card-group deck
    class="mb-3 ">
    <MarvelC /><!-- Captain Marvel -->
    <WeddingC /><!--Destination Wedding -->
    <DumboC /><!--Dumbo -->
    </b-card-group>

    <b-card-group deck
    class="mb-3 ">
    <EighthC /><!--Eighth Grade -->
    <Fisherman /><!--Fisherman’s Friend -->
    <GretaC /><!--Greta -->
    </b-card-group>

    <b-card-group deck
    class="mb-3 ">
    <HellboyC /><!--Heliboy-->
    <LifeC /><!--High Life -->
    <LittleC /><!--Little -->
    </b-card-group>

    <b-card-group deck
    class="mb-3 ">
    <ShotC /><!--Long shot-->
    <PoppinsC /><!--Mary Poppins-->
    <MidC /><!--Mid 90s -->
    </b-card-group>

  <b-card-group deck
  class="mb-3 ">
    <Peppa /><!--Peppa Pig Festival of Fun-->
    <PetC /><!--Pet Sematary-->
    <PokemonC /><!-- Pokemon Detective Pikachu-->
    </b-card-group>

    <b-card-group deck
    class="mb-3 ">
    <JoanC /><!--Red Joan-->
    <ShazamC /><!--Shazam-->
    <SisterC /><!--The sisters Brother -->
    </b-card-group>

  <b-card-group deck
  class="mb-3 ">
    <StudentC /><!--Student of the year 2 -->
    <CorruptedC/><!--The Corrupted-->
    <LloronaC /><!--The curse of la Llorona-->
    </b-card-group>

  <b-card-group deck
  class="mb-3 ">
    <HustleC /><!--The Hustle-->
    <TolkienC /><!--Tolkien-->
    <UsC /><!--Us-->
    </b-card-group>

  <b-card-group deck
  class="mb-3 ">
    <Rose /><!----Wild Rose -->
    <WomanC /><!--Woman at war -->
    <WonderC /><!--Wonder park -->
    </b-card-group>


      <!--<Ml --90ML -->
      <!--<Star --A star is Born-->
      <!-- <AlitaC --Alita Battle Angel -->

      <!--<Airaa Airaa -->
      <!--<Badla ---Badia -->
      <!--<Border --Border -->
      <!-- <BlueC />--Out Of Blue -->


      <!--True --All Is True 12A"-->
      <!--<Bell --Bell bottom-->
      <!--<Aquaman --Aquaman -->
      <!--<Band /--Band Vaaje-->
      <!--<CantoC />--Bel Canto -->

      <!--<ConcreteC /--Dragged Across Concrete -->

      <!--<BealeC --If Beale Street Could talk-->

      <!--Black --Blackklansman -->
      <!--<BoyC /--Beautiful Boy -->

      <!--Burning --Burning-->
      <!--<Caper />--Capernaum -->

      <!--<Dragon --Dragon Ball Super -->
      <!--<DragonworldC /--How to Train Your Dragon the Hidden -->

      <!--<EscapeC --Escape Room -->
      <!--<Lion /--Eaten by Lion -->

      <!--<EverybodyC />--Everybody Knows -->
      <!--<FamilyC /--Instant Family  -->

      <!--<FightingC /--Fighting With My Family -->

      <!--<GlassC --Glass-->
      <!--<GreenC /--Green Book-->


      <!--<Guddiyan />--Guddiyan Patole -->

      <!--<HappyC />--Happy Death Day -->
      <!--<Fight --The Fight-->
      <!--<Hannah --Hannah-->
      <!--<KeeperC --The Keeper -->
      <!--<KingC /--The Kid Who Would Be King-->

      <!--<Kobiety --Kobiety Mafii 2 -->
      <!--kodathi --Kodathi Samaksham Balan Vakkeel-->
      <!--Kumbalangi --Kumbalangi Nights-->
      <!--<Junglee /--Junglee -->
      <!--<Lego />--Lego-->

      <!--<Luka />--Luka Chuppi  -->
<!--  <Lords /--Lords of chaos-->

      <!--<Bala --Miss Bala-->
  <!--<FavouriteC />--The Favourite -->

      <!--Maiden --Maiden-->

      <!--<Milan -Milan Talkies-->
      <!--<MissingC />--Missing Link-->

      <!--<Notebook />--Notebook-->
      <!--<Prodigy --The Prodigy-->
      <!--<Rabb /--Rabb Da Radio-->
      <!--<Ralph />--Ralph Breaks The Internet: Wreck-It -->

      <!--<Ring --Ring-->
      <!--Serenityx--Serenity -->
      <!--<CatC />--Spy Cat -->

      <!--<Spider />--Spider-Man Into The Spider-Verse -->

      <!--<StyxC />--Styx -->


      <!--<Total /><-Total Dhamal  -->
  <!--<ScotsC />--Mary Queen Of Scots -->
      <!--<Kala /> Kala Shah Kala -->
      <!--Grinch --Grinch-->
      <!--<VanishingC --The Vanishing-->
      <!--<Crow --The White Crow-->
          <!--<Vice /--Vice-->


      </b-container>
      </section>

</template>

<script>

import FavouriteC from '@/components/Films/Favourite/FavouriteC'
import Mule from '@/components/Films/Mule'
import Vice from '@/components/Films/Vice'
import Blank from '@/components/Films/Blank'
import Ralph from '@/components/Films/Ralph'
import Spider from '@/components/Films/Spider'
import Destroyer from '@/components/Films/Destroyer'
import Preview from '@/components/Films/Preview'
import Creed from '@/components/Films/Creed'
import Colette from '@/components/Films/Colette'
import Lego from '@/components/Films/Lego'
import True from '@/components/Films/True'
import Caper from '@/components/Films/Caper'
import Black from '@/components/Films/Black'
import War from '@/components/Films/War'
import Aftermath from '@/components/Films/Aftermath'
import Serenityx from '@/components/Films/Serenityx'
import Gully from '@/components/Films/Gully'
import Kala from '@/components/Films/Kala'
import Ml from '@/components/Films/Ml'
import Luka from '@/components/Films/Luka'
import Badla from '@/components/Films/Badla'
import Border from '@/components/Films/Border'
import Bala from '@/components/Films/Bala'
import Guddiyan from '@/components/Films/Guddiyan'
import Kumbalangi from '@/components/Films/Kumbalangi'
import Total from '@/components/Films/Total'
import Bell from '@/components/Films/Bell'
import Kobiety from '@/components/Films/Kobiety'
import Kodathi from '@/components/Films/Kodathi'
import Maiden from '@/components/Films/Maiden'
import Fisherman from '@/components/Films/Fisherman'
import Fight from '@/components/Films/Fight'
import Prodigy from '@/components/Films/Prodigy'
import Band from '@/components/Films/Band'
import Milan from '@/components/Films/Milan'
import Burning from '@/components/Films/Burning'
import Ring from '@/components/Films/Ring'
import Hannah from '@/components/Films/Hannah'
import Rose from '@/components/Films/Rose'
import Crow from '@/components/Films/Crow'
import DumboC from '@/components/Films/Dumbo/DumboC'
import Junglee from '@/components/Films/Junglee'
import Lion from '@/components/Films/Lion'
import BlueC from '@/components/Films/Blue/BlueC'
import Notebook from '@/components/Films/Notebook'
import Lords from '@/components/Films/Lords'
import Lucifer from '@/components/Films/Lucifer'
import Rabb from '@/components/Films/Rabb'
import Airaa from '@/components/Films/Airaa/Airaa'
import Vanishing from '@/components/Films/Vanishing/Vanishing'
import VanishingC from '@/components/Films/Vanishing/VanishingC'
import Scots from '@/components/Films/Scots/Scots'
import ScotsC from '@/components/Films/Scots/ScotsC'
import Forgive from '@/components/Films/Forgive/Forgive'
import Boy from '@/components/Films/Boy/Boy'
import BoyC from '@/components/Films/Boy/BoyC'
import Dog from '@/components/Films/Dog/Dog'
import DogC from '@/components/Films/Dog/DogC'
import Ben from '@/components/Films/Ben/Ben'
import Bohemian from '@/components/Films/Bohemian/Bohemian'
import Cold from '@/components/Films/Cold/Cold'
import BealeC from '@/components/Films/Beale/BealeC'
import Bumblebee from '@/components/Films/Bumblebee/Bumblebee'
import Alita from '@/components/Films/Alita/Alita'
import AlitaC from '@/components/Films/Alita/AlitaC'
import Marvel from '@/components/Films/Marvel/Marvel'
import MarvelC from '@/components/Films/Marvel/MarvelC'
import Happy from '@/components/Films/Happy/Happy'
import HappyC from '@/components/Films/Happy/HappyC'
import Green from '@/components/Films/Green/Green'
import GreenC from '@/components/Films/Green/GreenC'
import Glass from '@/components/Films/Glass/Glass'
import GlassC from '@/components/Films/Glass/GlassC'
import Five from '@/components/Films/Five/Five'
import FiveC from '@/components/Films/Five/FiveC'
import Fighting from '@/components/Films/Fighting/Fighting'
import FightingC from '@/components/Films/Fighting/FightingC'
import Family from '@/components/Films/Family/Family'
import FamilyC from '@/components/Films/Family/FamilyC'
import Everybody from '@/components/Films/Everybody/Everybody'
import EverybodyC from '@/components/Films/Everybody/EverybodyC'
import Escape from '@/components/Films/Escape/Escape'
import EscapeC from '@/components/Films/Escape/EscapeC'
import Dragonworld from '@/components/Films/Dragonworld/Dragonworld'
import DragonworldC from '@/components/Films/Dragonworld/DragonworldC'
import Missing from '@/components/Films/Missing/Missing'
import MissingC from '@/components/Films/Missing/MissingC'
import Peppa from '@/components/Films/Peppa/Peppa'
import ShazamC from '@/components/Films/Shazam/ShazamC'
import PetC from '@/components/Films/Pet/PetC'
import KingC from '@/components/Films/King/KingC'
import KeeperC from '@/components/Films/Keeper/KeeperC'
import SisterC from '@/components/Films/Sister/SisterC'
import WonderC from '@/components/Films/Wonder/WonderC'
import UsC from '@/components/Films/Us/UsC'
import HellboyC from '@/components/Films/Hellboy/HellboyC'
import LittleC from '@/components/Films/Little/LittleC'
import PoppinsC from '@/components/Films/Poppins/PoppinsC'
import RomeoC from '@/components/Films/Romeo/RomeoC'
import ManjeC from '@/components/Films/Manje/ManjeC'
import SherdilC from '@/components/Films/Sherdil/SherdilC'
import SuperC from '@/components/Films/Super/SuperC'
import MidC from '@/components/Films/Mid/MidC'
import Kesari from '@/components/Films/Kesari'
import GretaC from '@/components/Films/Greta/GretaC'
import JoanC from '@/components/Films/Joan/JoanC'
import AvengersC from '@/components/Films/Avengers/AvengersC'
import EighthC from '@/components/Films/Eighth/EighthC'
import CantoC from '@/components/Films/Canto/CantoC'
import CatC from '@/components/Films/Cat/CatC'
import ConcreteC from '@/components/Films/Concrete/ConcreteC'
import StyxC from '@/components/Films/Styx/StyxC'
import HustleC from '@/components/Films/Hustle/HustleC'
import LifeC from '@/components/Films/Life/LifeC'
import LloronaC from '@/components/Films/Llorona/LloronaC'
import PokemonC from '@/components/Films/Pokemon/PokemonC'
import ShotC from '@/components/Films/Shot/ShotC'
import TolkienC from '@/components/Films/Tolkien/TolkienC'
import WomanC from '@/components/Films/Woman/WomanC'
import CorruptedC from '@/components/Films/Corrupted/CorruptedC'
import StudentC from '@/components/Films/Student/StudentC'
import GraceC from '@/components/Films/Grace/GraceC'
import Kalank from '@/components/Films/Kalank/Kalank'
import WeddingC from '@/components/Films/Wedding/WeddingC'










export default {
  head () {
    return {
      titleTemplate: '%s Movies Today',
      meta         : [
        { hid: 'description', name: 'description', content: ' Whats on today @ cineworld, odeon, picturehouses, showcase & Vue cinemas in east London, Bexleyheath, Greenwich 02, Ilford,romford, South Woodford and West India Quay, April 2019 and free to watch online movies' }
      ]
    }
  },
  components: {
    Aftermath,
    Airaa,
    Alita,
    AlitaC,
    AvengersC,
    Badla,
    Bala,
    Band,
    BealeC,
    Bell,
    Ben,
    Black,
    Blank,
    BlueC,
    Bohemian,
    Border,
    Boy,
    BoyC,
    Bumblebee,
    Burning,
    CantoC,
    Caper,
    CatC,
    Cold,
    Colette,
    ConcreteC,
    CorruptedC,
    Creed,
    Crow,
    Destroyer,
    Dog,
    DogC,
    Dragonworld,
    DragonworldC,
    EighthC,
    Escape,
    EscapeC,
    Everybody,
    EverybodyC,
    Family,
    FamilyC,
    FavouriteC,
    Fight,
    Fighting,
    FightingC,
    Fisherman,
    Five,
    FiveC,
    Forgive,
    Glass,
    GlassC,
    GraceC,
    Green,
    GreenC,
    GretaC,
    Guddiyan,
    Gully,
    JoanC,
    Hannah,
    Happy,
    HappyC,
    HellboyC,
    HustleC,
    Kala,
    KeeperC,
    Kesari,
    KingC,
    Kobiety,
    Kodathi,
    Kumbalangi,
    Lego,
    LifeC,
    LittleC,
    LloronaC,
    Lucifer,
    Lords,
    Luka,
    Maiden,
    ManjeC,
    Marvel,
    MarvelC,
    MidC,
    Milan,
    Missing,
    MissingC,
    Ml,
    Mule,
    Notebook,
    Peppa,
    PetC,
    PokemonC,
    PoppinsC,
    Preview,
    Prodigy,
    Rabb,
    Ralph,
    Ring,
    RomeoC,
    Rose,
    Scots,
    ScotsC,
    Serenityx,
    ShazamC,
    SherdilC,
    ShotC,
    SisterC,
    Spider,
    StudentC,
    StyxC,
    SuperC,
    Total,
    TolkienC,
    True,
    Vanishing,
    VanishingC,
    Vice,
    War,
    DumboC,
    Junglee,
    Lion,
    UsC,
    WeddingC,
    WomanC,
    WonderC,
      }
}
</script>
