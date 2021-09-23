<template>
  <div class="justify-center grey lighten-4 pt-12 ma-0 white">
    <v-row class="white">
      <v-col cols="12" class="text-center ma-0 pa-0 align-center align-content-center font-weight-bold text-h3 light-green--text">
        <div
          class="pt-10 text-center align-center align-content-center text-h5 grey--text"
        >
          BUSINESS PORTFOLIO:
        </div>
      </v-col>
      <v-col cols="2" class="justify-end align-end align-content-end">
        <v-img src="./sun.gif" width="100" />
      </v-col>
      <v-col cols="9" class="text-center align-center align-content-center font-weight-bold text-h3">
        <div
          class="text-center align-center align-content-center text-h5 light-green--text darken-4"
        >
          POWER GENERATION
        </div>
      </v-col>
      <v-col cols="12">
        <v-img src="./solar.png" width="300" />
      </v-col>
    </v-row>
    <v-row class="pa-2 ma-2 white">
      <v-col cols="10" class="text-start align-center align-content-center black--text darken-2">
        <div>
          <P>
            TFI Power (Ghana) Limited is a licensed Independent Power Producer (IPP)
            developing and operating renewable energy-based power solutions for national
            grids and industrial customers in the sub-Saharan African region. TFI is currently
            implementing 60MW grid-connected photovoltaic solar power plant in Ghana
            under a 25-year Power Purchase Agreement (PPA) with the State Utility Company.
            The initial phase will be commissioned for operation in Q42022. The company is
            simultaneously developing a 120MW Solar PV plus Energy Storage hybrid system
            for an industrial customer in the Republic of Congo.
          </P>
          <p>
            Phase one of the Hiowe Mahe-Shai Solar Power Plant shall soon commence construction in the Shai-Osudoku District of Greater Accra Region of Ghana.  The Plant is designed to generate 91 gigawatt hours of electric power annually when the fulL Capacity is completed.  The Plant output will be fed directly onto the national electric grid.
          </p>
          <P>The project is in line with the Government commitment to generating clean and affordable energy to power the national industrialization policy.  The siting of the Plant will have the additional benefit of becoming a magnet for businesses to locate and create jobs for the community.</P>
        </div>
      </v-col>
    </v-row>
    <carousa />
    <div class="pa-8 ma-10 white">
      <v-row class="d-flex" align="center" align-content="center" justify="center">
        <v-col cols="12" class="text-center align-center align-content-center font-weight-bold text-h3">
          <div
            class="text-center text-h5 green--text"
          >
            Minerals Resources Explorations & Mining
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="10">
          <p class="grey--text darken-4">
            <span class="blue--text">Volta Resources Limited</span> is a junior minerals exploration and mining company
            owning a gold concession covering an area of 70.89 square kilometers. The
            concession is located 25 square kilometers southwest of the high producing (30
            million ounce +) Obuasi Mines, operated by Anglo-gold Ashanti, and 6 kilometers
            north of Perseus Mining’s 5-million-ounce Edikan Mines. Volta has undertaken
            years of exploration and will soon commence a drilling program to ascertain the
            ore volume and grade. The company aims to become a significant gold mining
            company
          </p>
        </v-col>
      </v-row>
    </div>
    <div class="pa-8 ma-10 white">
      <v-row class="d-flex" align="center" align-content="center" justify="center">
        <v-col cols="12" class="text-center align-center align-content-center font-weight-bold text-h3">
          <div
            class="text-center text-h5 green--text"
          >
            Bio-Energy Development
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="10">
          <p class="grey--text darken-4">
            <span class="blue--text">TFI Agrotech Limited</span> is developing agriculture-based energy technologies to
            enhance food sufficiency while producing low carbon renewable energies for
            mobility applications. In conjunction with the Centre for Scientific and Industrial
            Research’s Savannah Agricultural Institute in Ghana, the company is undertaking
            trials of high-yielding sorghum seeds developed by University of Tokyo. Once
            harvested, the grains will be sold directly into the food industry, and the biomass
            processed into biochar to fertilize the land, and using a catalyst, transform the
            syngas produced into bio-methanol. Bio-methanol can fuel combustion engine
            automobiles, reformed into hydrogen for fuel cells, and can also fuel cooking stoves
            to reduce deforestation for firewood.
          </p>
        </v-col>
      </v-row>
    </div>
    <v-row class="pa-0 ma-0">
      <v-col cols="10" class="text-center ma-0 pa-0 align-center align-content-center font-weight-bold text-h3 light-green--text darken-4">
        <div
          class="pt-10 text-center align-center align-content-center text-h5 grey--text darken-4"
        >
          OUR LOCATION
        </div>
      </v-col>
    </v-row>
    <v-row>
      <v-col
        cols="12"
        class="pa-0 ma-0"
      >
        <div class="mapouter">
          <div class="gmap_canvas">
            <iframe
              id="gmap_canvas"
              width="100%"
              height="540"
              src="https://maps.google.com/maps?q=5%C2%B036'40.9%22N%200%C2%B011'45.0%22W&t=k&z=19&ie=UTF8&iwloc=&output=embed"
              frameborder="0"
              scrolling="no"
              marginheight="0"
              marginwidth="0"
            />
          </div>
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import carousa from '@/components/carousa.vue'
export default {
  components: {
    carousa
  }
}
</script>

<style scoped>
</style>
