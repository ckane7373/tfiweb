<template>
  <v-container
    justify="center"
    align="center"
    align-content="center"
    class="ma-0 pa-0 blue darken-4"
    width="50vh"
    fluid
  >
    <v-row justify="center" align="center" align-content="center" class="ma-0 pa-0">
      <v-col
        cols="12"
        class="ma-0 pa-1"
        justify="center"
        align="center"
        align-content="center"
      >
        <v-card
          class="text-left ma-0 pa-0"
          justify="center"
          align="center"
          align-content="center"
        >
          <v-card-title class="text-left blue darken-4">
            <div class="text-left headline white--text button">
              TEN<br>FORWARD<br>INTERNATIONAL<br>
              <span class="black--text">G  R  O  U  P</span>
            </div>
          </v-card-title>
        </v-card>
      </v-col>
    </v-row>
    <v-row justify="center" align-content="center" align="center" class="pa-2 ma-0">
      <v-col
        align-self="center"
        cols="12"
        justify="center"
        align-content="center"
        align="center"
        class="pa-0 ma-0"
      >
        <v-img src="logo.png" width="50%" class="text-right" />
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-list align="center" justify="center" align-content="center" class="ma-0 pa-0">
          <v-list-item
            align="center"
            justify="center"
            align-content="center"
            class="ma-0 pa-0"
          >
            <v-list-item-title
              align="center"
              justify="center"
              align-content="center"
              class="white--text ma-0 pa-0"
            >
              CONTACT US
            </v-list-item-title>
          </v-list-item>
        </v-list>
      </v-col>
    </v-row>

    <v-row justify="center" align="center" align-content="center" class="ma-0 pa-0">
      <v-col
        cols="12"
        class="ma-0"
        justify="center"
        align="center"
        align-content="center"
      >
        <v-card
          class="text-left ma-0 pa-0"
          justify="center"
          align="center"
          align-content="center"
        >
          <v-list
            class="pa-0 ma-0 red--text text--darken-4"
            justify="center"
            align="center"
            align-content="center"
          >
            <v-expand-transition>
              <v-list-item
                v-if="hover"
                class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal text-h2 white--text"
                style="height: 100%"
              >
                <v-list-item-action class="pa-0 ma-0">
                  <v-icon class="indigo--text">
                    mdi-phone
                  </v-icon>
                </v-list-item-action>

                <v-list-item-content>
                  <v-list-item-title class="indigo--text text-button">
                    547.007.033
                  </v-list-item-title>
                </v-list-item-content>
              </v-list-item>
            </v-expand-transition>
            <v-divider inset />

            <v-list-item class="pa-0 ma-0">
              <v-list-item-action class="pa-0 ma-0">
                <v-icon class="indigo--text">
                  mdi-phone
                </v-icon>
              </v-list-item-action>

              <v-list-item-content>
                <v-list-item-title class="indigo--text text-button">
                  547.007.033
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-divider inset />

            <v-list-item class="pa-0 ma-0">
              <v-list-item-action class="pa-0 ma-0">
                <v-icon class="indigo--text">
                  mdi-phone
                </v-icon>
              </v-list-item-action>

              <v-list-item-content>
                <v-list-item-title class="indigo--text text-button">
                  547.007.033
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-divider inset />

            <v-list-item class="pa-0 ma-0">
              <v-list-item-action class="pa-0 ma-0">
                <v-icon class="indigo--text">
                  mdi-phone
                </v-icon>
              </v-list-item-action>

              <v-list-item-content>
                <v-list-item-title class="indigo--text text-button">
                  547.007.033
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-divider inset />
            <v-list-item class="pa-0 ma-0">
              <v-list-item-action class="pa-0 ma-0">
                <v-icon class="indigo--text">
                  mdi-phone
                </v-icon>
              </v-list-item-action>

              <v-list-item-content>
                <v-list-item-title class="indigo--text text-button hov">
                  547.007.033
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-divider inset />

            <v-list-item class="pa-0 ma-0">
              <v-list-item-action class="pa-0 ma-0">
                <v-icon class="indigo--text">
                  mdi-email
                </v-icon>
              </v-list-item-action>

              <v-list-item-content>
                <v-list-item-title class="indigo--text text-caption">
                  info@tenforwardgroup.com
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-card>
      </v-col>
      <v-spacer />
    </v-row>
    <v-row justify="center" align-content="center" align="center" class="pa-2 ma-0">
      <v-col>
        <v-list align="center" justify="center" align-content="center" class="ma-0 pa-0">
          <v-list-item
            align="center"
            justify="center"
            align-content="center"
            class="ma-0 pa-0"
          >
            <v-list-item-title
              align="center"
              justify="center"
              align-content="center"
              class="pt-12 white--text text--darken-4 ma-0"
            >
              LOCATION
            </v-list-item-title>
          </v-list-item>
        </v-list>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
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
  </v-container>
</template>

<script>
export default {
  data () {
    return {
      dialog: false
    }
  }
}
</script>

<style scoped>

</style>
