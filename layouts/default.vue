<template>
  <div>
    <v-app id="app">
      <v-card class="overflow-hidden">
        <v-app-bar
          app
          shrink-on-scroll
          color="indigo"
        >

          <v-spacer></v-spacer>

          <v-toolbar-items>

            <v-btn
              class="white--text"
              text
              @click="$vuetify.goTo('#about')"
              width="50"
            >about</v-btn>
            <v-btn
              class="white--text"
              text
              @click="$vuetify.goTo('#projects')"
            >projects</v-btn>
            <v-btn
              class="white--text"
              text
              @click="$vuetify.goTo('#services')"
            >services</v-btn>
            <v-btn
              class="white--text"
              text
              width="50"
              @click="$vuetify.goTo('#contact')"
            >Contact</v-btn>
          </v-toolbar-items>
        </v-app-bar>

        <Nuxt />
      </v-card>

      <v-footer
        color="indigo"
        app
      >
        <span class="white--text">&copy; Martos</span>
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
