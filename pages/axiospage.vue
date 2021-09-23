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
      {{ item }}
      <img
        :src="`http://localhost:1337${item.image.url}`"
        alt=""
        srcset=""
      >
    </div>
  </div>
</template>

<script>
export default {
  async asyncData ({ $axios }) {
    const data = await $axios.$get('http://localhost:1337/people')
    return { data }
  }
}
</script>

<style scoped>
</style>
