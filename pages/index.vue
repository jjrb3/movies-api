<template>
  <div class="container">
    <card-group></card-group>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import CardGroup from "../components/CardGroup";

export default {
  layout: 'layouts/default',
  components: {
      CardGroup,
      Logo,
  }
};
</script>

<style>

</style>
