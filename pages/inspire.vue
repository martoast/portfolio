<template>
  <div>

    <v-card
      class="mx-auto"
      max-width="344"
      v-for="i in 3"
      v-bind:key=i
    >
      <v-img src="https://cdn.vuetifyjs.com/images/cards/forest-art.jpg"></v-img>

      <v-card-text>
        <h2 class="title primary--text">Magento Forests</h2>
        Travel to the best outdoor experience on planet Earth. A vacation you will never forget!
      </v-card-text>

      <v-card-title>
        <v-rating
          :value="4"
          dense
          color="orange"
          background-color="orange"
          hover
          class="mr-2"
        ></v-rating>
        <span class="primary--text subtitle-2">64 Reviews</span>
      </v-card-title>

      <v-fade-transition>
        <v-overlay
          v-if="hover"
          absolute
          color="#036358"
        >
          <v-btn>See more info</v-btn>
        </v-overlay>
      </v-fade-transition>
    </v-card>
  </div>

</template>
<script>
export default {
  data: () => ({
    overlay: false
  })
};
</script>
