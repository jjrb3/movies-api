<template>
  <b-card
    title="Title"
    img-src="https://wallpapersite.com/images/pages/pic_w/18223.jpg"
    img-alt="Image"
    img-top
  >
    <card-text></card-text>
    <detail-button></detail-button>
  </b-card>
</template>

<script>
    import CardText from "./CardText";
    import DetailButton from "./DetailButton";
    export default {
        name: "Card",
        components: {DetailButton, CardText}
    }
</script>

<style scoped>

</style>
