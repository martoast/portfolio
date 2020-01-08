<template>
  <div>
    <v-app>
      <v-app-bar
        app
        color="indigo"
      >

        <v-spacer></v-spacer>

        <v-toolbar-items>
          <v-btn
            class="white--text"
            text
            @click="$vuetify.goTo('#home')"
          >home</v-btn>
          <v-btn
            class="white--text"
            text
            @click="$vuetify.goTo('#about')"
          >about</v-btn>
          <v-btn
            class="white--text"
            text
          >projects</v-btn>
          <v-btn
            class="white--text"
            text
            @click="$vuetify.goTo('#contact')"
          >Contact</v-btn>
        </v-toolbar-items>
      </v-app-bar>

      <Nuxt />

      <v-footer
        color="indigo"
        app
      >
        <span class="white--text">&copy; 2019</span>
      </v-footer>
    </v-app>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      dialog: false
    };
  }
};
</script>
