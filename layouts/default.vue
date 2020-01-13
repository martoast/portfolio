<template>
  <div>
    <v-app>

      <v-app-bar
        app
        absolute
        shrink-on-scroll
        color="indigo"
      >

        <v-spacer></v-spacer>

        <v-toolbar-items>

          <v-btn
            class="white--text"
            text
            @click="$vuetify.goTo('#about')"
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
            @click="$vuetify.goTo('#contact')"
          >Contact</v-btn>
        </v-toolbar-items>
      </v-app-bar>

      <Nuxt />

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
