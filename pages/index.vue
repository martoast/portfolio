<template>
  <div>
    <div>
      <v-app>
        <v-content>
          <section id="home">
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
                  <h1 class="display-1 font-weight-thin mb-4">
                    Software Engineer
                  </h1>
                  <h2 class="subheading">Alejandro Martos Ayala</h2>
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
                <!-- <iframe
                  allowfullscreen="true"
                  title="panorama"
                  scrolling="no"
                  width="100%"
                  height="300"
                  src="https://storage.googleapis.com/vrview/2.0/index.html?preview=https://storage.googleapis.com/vrview/examples/coral-preview.jpg&amp;image=https://storage.googleapis.com/vrview/examples/coral.jpg&amp;is_stereo=true&amp;"
                  style="border: 0px;"
                ></iframe> -->
                <section id="about">
                  <v-card
                    max-width="750"
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

                    <p>
                      I am a passionate Software Engineer with a love for
                      technology and it's potential to improve human life. My
                      experience with software is focused primarily on Web
                      Development; designing, building and deploying Full-Stack
                      web applications. I specialize in creating software for
                      clients ranging from individuals and small-businesses all
                      the way to large enterprise corporations.
                    </p>

                    <v-row justify="center">
                      <v-card-title>What would you build if you had a software developer on
                        your hands?</v-card-title>
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
                <v-responsive class="overflow-y-auto">
                  <v-lazy
                    transition="fade-transition"
                    :options="{
          threshold: .5
        }"
                  >
                    <div>
                      <div class="text-center">
                        <v-row justify="center">
                          <v-card-title class="headline"> Tech Stack</v-card-title>
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
                          >mdi-language-python</v-icon>
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
                          >mdi-language-csharp</v-icon>
                        </v-progress-circular>
                      </div>
                    </div>
                  </v-lazy>
                </v-responsive>

                <v-row justify="center">
                  <v-card-title>Education</v-card-title>
                </v-row>
                <v-row justify="center">
                  <v-card
                    max-width="500"
                    tile
                    class="d-flex justify-center mb-6 overflow-hidden"
                  >
                    <v-list-item>
                      <v-list-item-content>
                        <v-list-item-title> Mesa College</v-list-item-title>
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
                    max-width="500"
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

              <v-responsive class="overflow-y-auto">
                <v-lazy
                  transition="fade-transition"
                  :options="{
          threshold: .5
        }"
                >
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
                                  :elevation="hover ? 24 : 4"
                                  @click="ProjectModal(card)"
                                >
                                  <v-img
                                    :src="card.src"
                                    class="white--text align-end"
                                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                                    height="300px"
                                  >
                                    <v-card-title v-text="card.title"></v-card-title>
                                  </v-img>
                                  <v-spacer></v-spacer>
                                  <v-card-actions> </v-card-actions>
                                  <v-icon
                                    large
                                    v-for="lang in card.languages"
                                    :key="lang"
                                  >{{ lang }}</v-icon>
                                </v-card>
                              </v-hover>
                            </v-col>
                          </v-row>
                        </v-container>
                      </v-card>
                    </section>
                  </div>
                </v-lazy>
              </v-responsive>
              <v-responsive class="overflow-y-auto">
                <v-lazy
                  transition="fade-transition"
                  :options="{
          threshold: .5
        }"
                >
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
                            {{ this.CardTitle }}
                          </v-card-title>

                          <v-carousel height="300">
                            <div id="sample">
                              <div
                                v-for="image in this.CardImages"
                                :key="image"
                              >
                                <v-carousel-item>
                                  <v-img :src="image"> </v-img>
                                </v-carousel-item>
                              </div>
                            </div>
                          </v-carousel>

                          <v-card-text>
                            {{ this.CardText }}
                          </v-card-text>

                          <v-card-actions>
                            <v-spacer></v-spacer>
                            <v-btn
                              block
                              rounded
                            ><a :href="this.link">{{ this.btntxt }}</a>
                              <v-icon>mdi-github-circle</v-icon>
                            </v-btn>
                          </v-card-actions>
                        </v-card>
                      </v-dialog>
                    </div>
                  </div>
                </v-lazy>
              </v-responsive>

              <div>
                <v-responsive class="overflow-y-auto">
                  <v-lazy
                    transition="fade-transition"
                    :options="{
          threshold: .5
        }"
                  >
                    <section>
                      <v-card
                        flat
                        class="transparent"
                      >
                        <v-row justify="center">
                          <v-card-title></v-card-title>
                        </v-row>
                        <v-container grid-list-xl>
                          <v-layout
                            row
                            wrap
                            align-center
                            class="my-12"
                            id="services"
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
                                  >mdi-eye</v-icon>
                                </v-card-text>
                                <v-card-title
                                  primary-title
                                  class="layout justify-center"
                                >
                                  <div class="headline text-center">
                                    Research
                                  </div>
                                </v-card-title>
                                <v-card-text>
                                  Understand the client’s subject matter completely
                                  and build on the knowledge related to it, becoming
                                  intimately familiar with the subject matter.
                                  Determine methods to address the specific customer’s
                                  needs and requirements.
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
                                  >mdi-android-studio</v-icon>
                                </v-card-text>
                                <v-card-title
                                  primary-title
                                  class="layout justify-center"
                                >
                                  <div class="headline">Design</div>
                                </v-card-title>
                                <v-card-text>
                                  Misleadingly thought of as the superficial
                                  appearance of a product, design actually encompasses
                                  a lot more. It is a cross functional process that
                                  includes market research, technical research, design
                                  of a concept, and prototype mockup.
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
                                  >mdi-laptop-chromebook</v-icon>
                                </v-card-text>
                                <v-card-title
                                  primary-title
                                  class="layout justify-center"
                                >
                                  <div class="headline text-center">
                                    Develop
                                  </div>
                                </v-card-title>
                                <v-card-text>
                                  Findings from the research and design phases are
                                  utilized for the production of specific products
                                  including materials, systems, and methods. Engineer
                                  utilizing the research and designs to produce
                                  commercial products for the customer.
                                </v-card-text>
                              </v-card>
                            </v-flex>
                          </v-layout>
                        </v-container>
                      </v-card>
                    </section>
                  </v-lazy>
                </v-responsive>
              </div>
            </v-flex>
          </v-layout>
          <div>
            <v-responsive class="overflow-y-auto">
              <v-lazy
                transition="fade-transition"
                :options="{
          threshold: .5
        }"
              >
                <section id="contact">
                  <v-container>
                    <v-layout
                      row
                      justify-center
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
                            <div class="headline">Contact Me</div>
                          </v-card-title>

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
              </v-lazy>
            </v-responsive>
          </div>
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
import ferrominio5 from "~/assets/images/ferrominio/ferrominio5.png";
import ferrominio6 from "~/assets/images/ferrominio/ferrominio6.png";
import ferrohistory from "~/assets/images/ferrominio/ferrohistory.png";
import delacosta from "~/assets/images/delacosta/delacosta.png";
import delacosta2 from "~/assets/images/delacosta/delacosta2.png";
import delacosta3 from "~/assets/images/delacosta/delacosta3.png";
import btree from "~/assets/images/btree/btree.png";
import Virtual from "~/assets/images/Vr/Virtual.png";
import Balls from "~/assets/images/Vr/ballsVr.png";

export default {
  head() {
    return {
      title: `🚀Alejandro Martos🚀`,
      meta: [
        {
          hid: "description",
          name: "description",
          content:
            "Alejandro Martos is a Software Engineer in Tijuana Mexico that specializes in full stack web development."
        }
      ]
    };
  },
  data() {
    return {
      interval: {},
      value: 0,
      cards: [
        {
          title: "Point of Sale",
          src: eazypos,
          link: "https://github.com/martoast/pos",
          flex: 12,
          images: [landingmodal, food, menuconfig],
          languages: [
            "mdi-vuejs",
            "mdi-language-javascript",
            "mdi-language-html5",
            "mdi-language-css3"
          ],
          text:
            "An E-commerce storefront system designed to get your store selling as soon as possible. Automate the annoying process of keeping track of everything you sell! Users register with a verififed email and are directed to create a menu for their store. Once saved, the user navigates to the Cash Register where they are able to begin completing sales immediately! All sales data is recorded and stored in the cloud under user's email authentication. ",
          btntxt: "Visit Repo"
        },

        {
          title: "Virtual Reality",
          src: Virtual,
          link: "",
          flex: 6,
          images: [Virtual, Balls],
          languages: [
            "mdi-hololens",
            "mdi-language-csharp",
            "mdi-cube-outline"
          ],
          text:
            "Designed and developed a virtual reality ‘play room’ for the purpose of understanding the fundamental mechanics that are crucial for any good VR experience. The play room includes a simulated bowling alley in which players walk up to a table and pick up a ball and knock down pins. All physics and animations were done using the game engine Unity.",
          btntxt: "Visit Site"
        },
        {
          title: "Ferrominio",
          src: ferrominio,
          link: "http://www.ferrominio.com/en",
          flex: 6,
          images: [ferrominio, ferrominio5, ferrominio6, ferrohistory],
          languages: [
            "mdi-language-javascript",
            "mdi-language-html5",
            "mdi-language-css3"
          ],
          text:
            "Ferrominio Proyectos is an important steel manufacturer and construction company in Baja California. The website was designed to transmit their standards and reliablility. To increase the authenticity of the website I collected real images of their installations to use on the site instead of using generic pictures online.",
          btntxt: "Visit Site"
        },
        {
          title: "Instragram Bot",
          src: instabot,
          link: "https://github.com/martoast/instagrambot",
          flex: 6,
          images: [instabot],
          languages: ["mdi-language-python-text"],
          text:
            "See who Unfollowed You! Use the Selenium Web Driver to create browser-based regression automation. Bot opens up chrome, goes to instagram.com, logs in with the provided username and password, and compares the list of people you follow to the list of people who follow you back, returning a json object of those usernames that dont follow you back. ",
          btntxt: "Visit Repo"
        },

        {
          title: "Data Structures",
          src: btree,
          link:
            "https://github.com/martoast/Bipartite-checking-using-Graph-Colouring-and-Breadth-First-Search-BFS-O-V-E-time-",
          flex: 6,
          images: [btree],
          languages: ["mdi-language-python-text"],
          text:
            "Bipartite checking using Graph colouring and Breath First Search. The Time Complexity will be O(V + E) where V is the number of vertices and E is the number of edges.",
          btntxt: "Visit Repo"
        }
      ],
      dialog: false,
      CardTitle: null,
      CardText: null,
      CardImages: null,
      link: null,
      btntxt: null,
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
      this.link = card.link;
      this.btntxt = card.btntxt;
    }
  }
};
</script>
<style scoped>
.v-progress-circular {
  margin: 1rem;
}
</style>
