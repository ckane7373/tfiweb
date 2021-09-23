<template>
  <div>
    <div
      class="justify-center d-flex pl-15 pt-15 white red--text align-center align-content-center align-self-center"
    >
      <h1
        class="justify-center pl-16 pt-15 white red--text text-h1 align-center align-content-center align-self-center"
      >
        axios
      </h1>
    </div>
    <div
      v-for="item in data"
      :key="item.id"
      class="white black--text pa-4 ma-2"
    >
      {{ item.role }}
      <img :src="item.pictures" alt="" srcset="">
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return { contents: {} }
  },
  async fetch () {
    const api = 'http://localhost:1337/people'
    this.contents = await this.$axios.$get(api)
  }
}
</script>

<style scoped>
</style>
