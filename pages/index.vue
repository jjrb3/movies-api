<template>
  <div class="container">
    <b-card-group deck class="mt-4">
      <b-card
        title="Title"
        img-src="https://wallpapersite.com/images/pages/pic_w/15948.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          This is a wider card with supporting text below as a natural lead-in to additional content.
          This content is a little bit longer.
        </b-card-text>
        <b-button to="/detail">View Detail</b-button>
      </b-card>

      <b-card
        title="Title"
        img-src="https://wallpapersite.com/images/pages/pic_w/15927.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>This card has supporting text below as a natural lead-in to additional content.</b-card-text>
        <b-button to="/detail">View Detail</b-button>
      </b-card>

      <b-card
        title="Title"
        img-src="https://wallpapercave.com/wp/wp1808933.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          This is a wider card with supporting text below as a natural lead-in to additional content.
          This card has even longer content than the first to show that equal height action.
        </b-card-text>
        <b-button to="/detail">View Detail</b-button>
      </b-card>

      <b-card
        title="Title"
        img-src="https://wallpapersite.com/images/pages/pic_w/17994.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          This is a wider card with supporting text below as a natural lead-in to additional content.
          This content is a little bit longer.
        </b-card-text>
        <b-button to="/detail">View Detail</b-button>
      </b-card>

      <b-card
        title="Title"
        img-src="https://wallpapersite.com/images/pages/pic_w/18223.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>This card has supporting text below as a natural lead-in to additional content.</b-card-text>
      </b-card>

      <b-card
        title="Title"
        img-src="https://wallpapersite.com/images/pages/pic_w/17618.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          This is a wider card with supporting text below as a natural lead-in to additional content.
          This card has even longer content than the first to show that equal height action.
        </b-card-text>
        <b-button to="/detail">View Detail</b-button>
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  layout: 'layouts/default',
  components: {
    Logo
  }
};
</script>

<style>

</style>
