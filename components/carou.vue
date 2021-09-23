<template>
  <div class="pa-0 ma-0">
    <v-carousel
      show-arrows-on-hover
      hide-delimiter-background
      hide-delimiters
      interval="9000"
      continuous
      cycle
      height="50"
    >
      <v-carousel-item v-for="(item, i) in items" :key="i" src="item.src">
        <div class="d-flex justify-space-around align-center">
          <span class="pa-2 ma-2 green--text text--darken-3 text-subtitle-1">{{ item.msg }}</span>
        </div>
      </v-carousel-item>
    </v-carousel>
  </div>
</template>
<script>
export default {
  data () {
    return {
      items: [
        {
          msg: 'CLEAN ENERGY PROJECTS'
        },
        {
          msg: 'WE EMPOWER THE NEXT GENERATION'
        },
        {
          msg: 'WE HELP DRIVE INNOVATION'
        },
        {
          msg: 'WE ARE HERE TO SERVE'
        }
      ]
    }
  }
}
</script>

  <style scoped>
  * {
    box-sizing: border-box;
    padding: 0;
    margin-top: 0;
  }
  </style>
