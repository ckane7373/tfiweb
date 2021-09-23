<template>
  <v-carousel
    hide-delimiters
    show-arrows-on-hover
    hide-delimiter-background
    continuous
    cycle
  >
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    />
  </v-carousel>
</template>
<script>
export default {
  data () {
    return {
      items: [
        {
          src: '7.jpeg'
        },
        {
          src: '1.jpg'
        },
        {
          src: '2.jpg'
        }
      ]
    }
  }
}
</script>
