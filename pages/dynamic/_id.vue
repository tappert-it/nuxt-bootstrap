<template>
  <div>
    <b-card
      title="Dynamic Card"
      :img-src="imglink"
      img-alt="Image"
      img-top
      tag="article"
      style="max-width: 20rem;"
      class="mb-2"
    >
      <b-card-text>
        Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
      </b-card-text>
    </b-card>
  </div>
</template>

<script>
  export default {
    name: 'tab-content-dynamic',
    data() {
      return {
        id: this.$route.params.id,
        imglink: "https://unsplash.com/photos/" + this.$route.params.id + "/download?force=true&w=640"
      }
    },
  }
</script>

<style scoped>

</style>
