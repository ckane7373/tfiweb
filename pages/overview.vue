<template>
  <div class="justify-center pt-12 ma-0 white">
    <div class="pa-8 ma-10 grey lighten-3">
      <v-row class="d-flex" align="center" align-content="center" justify="center">
        <v-col
          cols="3"
          sm="2"
          md="1"
          lg="1"
          xl="1"
          class="d-flex"
          align="center"
          align-content="center"
          justify="center"
        >
          <v-img src="./overview1.png" />
        </v-col>
        <v-col cols="12" class="text-center align-center align-content-center font-weight-bold text-h3">
          <div
            class="text-center align-center align-content-center text-h5 cyan--text darken-2"
          >
            GROUP OVERVIEW
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="10" class="black--text darken-2">
          <p class="grey--text darken-2">
            Ten Forward International GROUP is an Infrastructure Development and Investment company based in Accra.  The group is active in the areas of Renewable Power Generation, Minerals Explorations, Software Development and Cyber Security Services, and Specification of High Performance Architectural Glass to the industry.
          </p>
        </v-col>
      </v-row>
    </div>
    <v-row class="ma-0 pa-0 d-flex" align="center" align-content="center" justify="center">
      <v-col
        xs="4"
        sm="3"
        md="2"
        lg="1"
        xl="1"
        cols="4"
        align="center"
        align-content="center"
        justify="center"
        class="flex-wrap ma-0 pa-0 d-flex align-center align-content-center"
      >
        <v-img
          width="200"
          src="./list.png"
        />
      </v-col>
      <v-col
        class="flex-wrap pa-0 ma-0 black--text d-flex "
        xs="11"
        sm="11"
        md="9"
        lg="10"
        xl="10"
        cols="11"
        align="end"
        align-content="start"
        justify="end"
      >
        <div class="pt-8">
          <p class="text-left">
            Ten Forward Group focuses on infrastructure projects that accelerates socio-economic development, and have sustainable environmental benefits.  The Group leverages its local knowledge & experiences to identify key investment opportunities, undertake the project development, arrange project financing, and execute/manage the business to optimize returns to all stakeholders.
          </p><p class="text-left">
            Ten Forward Group works in close collaboration with the central, local governments, and the communities to implement infrastructure projects that creates employment and wealth for society at large.
          </p>
        </div>
      </v-col>
    </v-row>
    <div class="pa-8 ma-10 grey lighten-3">
      <v-row class="d-flex" align="center" align-content="center" justify="center">
        <v-col
          cols="3"
          sm="2"
          md="1"
          lg="1"
          xl="1"
          class="d-flex"
          align="center"
          align-content="center"
          justify="center"
        />
        <v-col cols="12" class="text-center align-center align-content-center font-weight-bold text-h3">
          <div
            class="text-center align-center align-content-center text-h5 cyan--text darken-2"
          >
            COUNTRY SUMMARY
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="10" class="black--text darken-2">
          <p class="grey--text darken-2">
            Ghana, located in the Gulf of Guinea, truly lays claim to the title “Centre of the
            world” as its latitude and longitude are the closest landmass to the intersection of
            the equator and the Greenwich Meridian. Ghana recently became the host nation
            for the Secretariat of the African Continental Free Trade Agreement. The Country’s
            traditional exports are gold, oil, diamond, bauxite, manganese, cocoa, and timber.
            The nation of 30 million inhabitants has an average age of 21 years, a literacy rate
            of 75% and a GDP equivalent to US$75 billion. The per capita income is US$2500.
            Ghana is a multi-party electoral state with an Executive and Legislative branch and
            an independent Judiciary.
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
export default {
  components: {
  }
}
</script>

<style scoped>
</style>
