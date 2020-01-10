<template>
  <div>
    <div>
      <v-app light>
        <v-content>
          <section id='home'>
            <v-parallax
              dark
              src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
            >
              <v-row
                align="center"
                justify="center"
              >
                <v-col
                  class="text-center"
                  cols="12"
                >
                  <h1 class="display-1 font-weight-thin mb-4">Alejandro Martos Ayala</h1>
                  <h2 class="subheading">Software Engineer</h2>
                </v-col>
              </v-row>
            </v-parallax>
          </section>

          <v-layout
            column
            wrap
            class="my-12"
            align-center
          >
            <v-flex
              xs12
              sm4
              class="my-4"
            >
              <div class="text-center">
                <section id='about'>
                  <v-card
                    max-width="600"
                    tile
                  >
                    <v-row justify="center">
                      <v-card-text class="text-center">
                        <v-icon
                          x-large
                          class="blue--text text--lighten-2"
                        >mdi-account-outline</v-icon>
                      </v-card-text>
                      <v-card-title class="headline">About Me</v-card-title>

                    </v-row>

                    <v-container fluid>

                      <p>
                        I am a passionate Web developer with a love for technology
                        and a passion for innovation. My experience with sofware is
                        focused primarily on Web Development; designing, building and deploying Full-Stack web applications.
                        I specialize in creating software for clients ranging from individuals and small-businesses all the way
                        to large enterprise corporations.

                      </p>

                    </v-container>

                    <v-row justify="center">
                      <v-card-subtitle>What would you build if you had a software
                        developer on your hands?</v-card-subtitle>
                    </v-row>

                  </v-card>

                </section>
              </div>
            </v-flex>

            <v-flex xs12>
              <v-card
                flat
                class="transparent"
              >
                <div class="text-center">

                  <v-row justify="center">
                    <v-card-title class="headline"> Skills</v-card-title>
                  </v-row>
                </div>

                <div class="text-center">
                  <v-progress-circular
                    :rotate="-90"
                    :size="100"
                    :width="15"
                    :value="value"
                    color="teal"
                  >
                    <v-icon
                      x-large
                      class="teal--text "
                    >mdi-vuejs</v-icon>
                  </v-progress-circular>

                  <v-progress-circular
                    :rotate="-90"
                    :size="100"
                    :width="15"
                    :value="value"
                    color="yellow"
                  >
                    <v-icon
                      x-large
                      class="yellow accent-3--text "
                    >mdi-language-javascript</v-icon>
                  </v-progress-circular>

                  <v-progress-circular
                    :rotate="-90"
                    :size="100"
                    :width="15"
                    :value="value"
                    color="purple"
                  >
                    <v-icon
                      x-large
                      class="purple--text "
                    >mdi-language-python-text</v-icon>
                  </v-progress-circular>

                  <v-progress-circular
                    :rotate="-90"
                    :size="100"
                    :width="15"
                    :value="value"
                    color="red"
                  >
                    <v-icon
                      x-large
                      class="red--text text--lighten-2"
                    >mdi-language-html5</v-icon>
                  </v-progress-circular>

                  <v-progress-circular
                    :rotate="-90"
                    :size="100"
                    :width="15"
                    :value="value"
                    color="primary"
                  >
                    <v-icon
                      x-large
                      class="primary--text "
                    >mdi-language-css3</v-icon>
                  </v-progress-circular>

                </div>

                <v-row justify="center">

                  <v-card-title>Education</v-card-title>
                </v-row>
                <v-row justify="center">
                  <v-card
                    max-width="600"
                    tile
                    class="d-flex justify-center mb-6"
                  >
                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>Mesa College</v-list-item-title>
                        <v-list-item-subtitle>San Diego, California</v-list-item-subtitle>
                      </v-list-item-content>
                    </v-list-item>

                    <v-list-item two-line>
                      <v-list-item-content>
                        <v-list-item-title>Associate of Science</v-list-item-title>
                        <v-list-item-subtitle>Physics</v-list-item-subtitle>

                      </v-list-item-content>
                    </v-list-item>

                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>2014 - 2017</v-list-item-title>

                      </v-list-item-content>
                    </v-list-item>

                  </v-card>
                </v-row>
                <v-row justify="center">
                  <v-card
                    max-width="600"
                    tile
                    class="d-flex justify-center mb-6"
                  >
                    <v-list-item two-line>
                      <v-list-item-content>
                        <v-list-item-title>CETYS University</v-list-item-title>
                        <v-list-item-subtitle>Tijuana, Mexico</v-list-item-subtitle>
                      </v-list-item-content>
                    </v-list-item>

                    <v-list-item two-line>
                      <v-list-item-content>
                        <v-list-item-title>Bachelor of Science</v-list-item-title>
                        <v-list-item-subtitle>Computer Engineering</v-list-item-subtitle>
                      </v-list-item-content>
                    </v-list-item>

                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title>2016 - Present</v-list-item-title>

                      </v-list-item-content>
                    </v-list-item>

                  </v-card>
                </v-row>
              </v-card>

              <div class="text-center">
                <section id="projects">
                  <v-card>
                    <v-row justify="center">
                      <v-icon
                        x-large
                        class="blue--text text--lighten-2"
                      >mdi-code-tags</v-icon>
                    </v-row>
                    <v-row justify="center">
                      <v-card-title class="headline">
                        Recent Projects
                      </v-card-title>
                    </v-row>

                    <v-container fluid>
                      <v-row dense>
                        <v-col
                          v-for="card in cards"
                          :key="card.title"
                          :cols="card.flex"
                        >
                          <v-hover v-slot:default="{ hover }">
                            <v-card
                              :elevation="hover ? 12 : 2"
                              @click="ProjectModal(card)"
                            >
                              <v-img
                                :src="card.src"
                                class="white--text align-end"
                                gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                                height="200px"
                              >

                                <v-card-title v-text="card.title"></v-card-title>
                              </v-img>
                              <v-spacer></v-spacer>
                              <v-card-actions>

                              </v-card-actions>
                              <v-icon
                                large
                                v-for="lang in card.languages"
                                :key="lang"
                              >{{lang}}</v-icon>

                            </v-card>
                          </v-hover>

                        </v-col>
                      </v-row>
                    </v-container>
                  </v-card>
                </section>
              </div>
              <div>
                <div class="text-center">
                  <v-dialog
                    v-model="dialog"
                    width="550"
                  >

                    <v-card>
                      <v-card-title
                        class="headline grey lighten-2"
                        primary-title
                      >
                        {{this.CardTitle}}
                      </v-card-title>
                      <v-row
                        align="center"
                        justify="center"
                      >
                        <v-carousel>
                          <div id="sample">

                            <div
                              v-for="image in this.CardImages"
                              :key="image"
                            >
                              <v-carousel-item>
                                <v-img :src="image">

                                </v-img>
                              </v-carousel-item>

                            </div>

                          </div>

                        </v-carousel>
                      </v-row>

                      <v-card-text>
                        {{this.CardText}}
                      </v-card-text>

                      <v-card-actions>
                        <v-spacer></v-spacer>
                        <v-btn
                          block
                          rounded
                        >See Code
                          <v-icon>mdi-github-circle</v-icon>
                        </v-btn>

                      </v-card-actions>
                    </v-card>
                  </v-dialog>
                </div>
              </div>

              <v-container grid-list-xl>
                <v-layout
                  row
                  wrap
                  align-center
                >
                  <v-flex
                    xs12
                    md4
                  >
                    <v-card
                      flat
                      class="transparent"
                    >
                      <v-card-text class="text-center">
                        <v-icon
                          x-large
                          class="blue--text text--lighten-2"
                        >mdi-monitor-multiple</v-icon>
                      </v-card-text>
                      <v-card-title
                        primary-title
                        class="layout justify-center"
                      >
                        <div class="headline text-center">
                          Administra tu menú
                        </div>
                      </v-card-title>
                      <v-card-text>
                        Personaliza tus menús y explota los modificadores para
                        aumentar tu ticket promedio. Usa fotos de tus
                        elementos más vistosos para enamorar a tus comensales
                        en la mesa.
                      </v-card-text>
                    </v-card>
                  </v-flex>
                  <v-flex
                    xs12
                    md4
                  >
                    <v-card
                      flat
                      class="transparent"
                    >
                      <v-card-text class="text-center">
                        <v-icon
                          x-large
                          class="blue--text text--lighten-2"
                        >mdi-flash</v-icon>
                      </v-card-text>
                      <v-card-title
                        primary-title
                        class="layout justify-center"
                      >
                        <div class="headline">Acelera las compras</div>
                      </v-card-title>
                      <v-card-text>
                        Envía las órdenes ala cocina más rápido y con menos
                        errores. especificaciones de pedido y complementos
                        totalmente personalizables.
                      </v-card-text>
                    </v-card>
                  </v-flex>
                  <v-flex
                    xs12
                    md4
                  >
                    <v-card
                      flat
                      class="transparent"
                    >
                      <v-card-text class="text-center">
                        <v-icon
                          x-large
                          class="blue--text text--lighten-2"
                        >mdi-wrench</v-icon>
                      </v-card-text>
                      <v-card-title
                        primary-title
                        class="layout justify-center"
                      >
                        <div class="headline text-center">
                          Analíticos en tiempo real
                        </div>
                      </v-card-title>
                      <v-card-text>
                        Vea qué ventas se han realizado desde cualquier lugar
                        donde esté utilizando su inicio de sesión de
                        administrador especial para ayudar a su negocio tomar
                        decisiones mas rapido.
                      </v-card-text>
                    </v-card>
                  </v-flex>
                </v-layout>
              </v-container>
            </v-flex>
          </v-layout>
          <section id='contact'>
            <v-container grid-list-xl>
              <v-layout
                row
                wrap
                justify-center
                class="my-12"
              >
                <v-flex
                  xs12
                  sm4
                >
                  <v-card
                    flat
                    class="transparent"
                  >
                    <v-card-title
                      primary-title
                      class="layout justify-center"
                    >
                      <div class="headline">
                        Información General
                      </div>
                    </v-card-title>
                    <v-card-text>
                      Somos una empresa que cree que es hora de que las soluciones
                      de software lleguen a México. Vemos el potencial de aportar
                      valor a su negocio ahorrándole tiempo y dinero en sistemas
                      obsoletos. Ofrecemos una solución confiable y económica a un
                      problema de logística que el desarrollo de software ahora
                      puede ayudar a resolver.
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex
                  xs12
                  sm4
                  offset-sm1
                >
                  <v-card
                    flat
                    class="transparent"
                  >
                    <v-card-title
                      primary-title
                      class="layout justify-center"
                    >
                      <div class="headline">Contact us</div>
                    </v-card-title>
                    <v-card-text>
                      Si tiene alguna pregunta o inquietud, llámenos para que
                      podamos atenderlo personalmente
                    </v-card-text>
                    <v-list class="transparent">
                      <v-list-item>
                        <v-list-item-action>
                          <v-icon class="blue--text text--lighten-2">mdi-phone</v-icon>
                        </v-list-item-action>
                        <v-list-item-content>
                          <v-list-item-title>619-888-5248</v-list-item-title>
                        </v-list-item-content>
                      </v-list-item>
                      <v-list-item>
                        <v-list-item-action>
                          <v-icon class="blue--text text--lighten-2">mdi-map-marker</v-icon>
                        </v-list-item-action>
                        <v-list-item-content>
                          <v-list-item-title>Tijuana, MX</v-list-item-title>
                        </v-list-item-content>
                      </v-list-item>
                      <v-list-item>
                        <v-list-item-action>
                          <v-icon class="blue--text text--lighten-2">mdi-email</v-icon>
                        </v-list-item-action>
                        <v-list-item-content>
                          <v-list-item-title>alexmartos96@gmail.com</v-list-item-title>
                        </v-list-item-content>
                      </v-list-item>
                    </v-list>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </section>

        </v-content>
      </v-app>
    </div>
  </div>
</template>

<script>
import eazypos from "~/assets/images/eazypos/eazypos.png";
import food from "~/assets/images/eazypos/food.png";
import menuconfig from "~/assets/images/eazypos/menuconfig.png";
import landingmodal from "~/assets/images/eazypos/landingmodal.png";
import instabot from "~/assets/images/instabot/instabot.png";
import ferrominio from "~/assets/images/ferrominio/ferrominio.png";
import ferrohistory from "~/assets/images/ferrominio/ferrohistory.png";
import delacosta from "~/assets/images/delacosta/delacosta.png";

export default {
  data() {
    return {
      interval: {},
      value: 0,
      cards: [
        {
          title: "Point of Sale",
          src: eazypos,
          flex: 6,
          images: [landingmodal, food, menuconfig],
          languages: [
            "mdi-vuejs",
            "mdi-language-javascript",
            "mdi-language-html5",
            "mdi-language-css3"
          ],
          text:
            "Morbi mattis ullamcorper velit. Donec orci lectus, aliquam ut, faucibus non"
        },
        {
          title: "Instragram Bot",
          src: instabot,
          flex: 6,
          images: [landingmodal, food, menuconfig],
          languages: ["mdi-language-python-text"],
          text: "ass"
        },
        {
          title: "Ferrominio Proyectos",
          src: ferrominio,
          flex: 6,
          images: [ferrominio, ferrohistory],
          languages: [
            "mdi-language-javascript",
            "mdi-language-html5",
            "mdi-language-css3"
          ],
          text:
            "Morbi mattis ullamcorper velit. Donec orci lectus, aliquam ut, faucibus non, euismod id, nulla. Fusce convallis metus id felis luctus adipiscing. Aenean massa. Vestibulum purus quam, scelerisque ut, mollis sed, nonummy id, metus. Nulla consequat massa quis enim. Praesent venenatis metus at tortor pulvinar varius. Donec venenatis vulputate lorem. Phasellus accumsan cursus velit. Pellentesque ut neque."
        },
        {
          title: "De la Costa",
          src: delacosta,
          flex: 6,
          images: [ferrominio, landingmodal, food, menuconfig],
          languages: [
            "mdi-language-javascript",
            "mdi-language-html5",
            "mdi-language-css3"
          ],
          text:
            "Morbi mattis ullamcorper velit. Donec orci lectus, aliquam ut, faucibus non, euismod id, nulla. Fusce convallis metus id felis luctus adipiscing. Aenean massa. Vestibulum purus quam, scelerisque ut, mollis sed, nonummy id, metus. Nulla consequat massa quis enim. Praesent venenatis metus at tortor pulvinar varius. Donec venenatis vulputate lorem. Phasellus accumsan cursus velit. Pellentesque ut neque."
        }
      ],
      dialog: false,
      CardTitle: null,
      CardText: null,
      CardImages: null,
      colors: ["primary", "secondary", "yellow darken-2", "red", "orange"]
    };
  },
  beforeDestroy() {
    clearInterval(this.interval);
  },
  mounted() {
    this.interval = setInterval(() => {
      if (this.value === 100) {
        return (this.value = 0);
      }
      this.value += 10;
    }, 1000);
  },
  methods: {
    ProjectModal(card) {
      console.log(card.text);
      this.CardTitle = card.title;
      this.CardText = card.text;
      this.dialog = true;
      this.CardImages = card.images;
    }
  }
};
</script>
<style scoped>
.v-progress-circular {
  margin: 1rem;
}
</style>
