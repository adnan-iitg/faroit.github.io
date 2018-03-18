<template>
  <v-app dark>
      <v-content>
        <v-container>
          <v-parallax height="600">

          <v-layout align-center>

            <v-flex xs12>
              <div class="text-xs-center">
                <v-avatar size="160px">
                  <img
                    class="img-circle elevation-7 mb-1"
                    src="./assets/frs.jpg"
                  >
                </v-avatar>
                <div class="headline">Fabian-Robert <span style="font-weight:bold">Stöter</span></div>
                <div class="subheading text-xs-center grey--text pt-1 pb-3">Audio Researcher</div>
                <v-layout
                  justify-center
                  align-center
                  row wrap
                >
                  <v-btn large style="background-color: #55acee" href="https://www.twitter.com/faroit"><v-icon left>fab fa-github</v-icon>Twitter</v-btn>
                  <v-btn large style="background-color: #a6ce39" href="https://orcid.org/0000-0002-2534-1165">Orcid ID</v-btn>
                  <v-btn large style="background-color: #4285f4" href="https://scholar.google.com/citations?user=7HsSdqwAAAAJ">Google Scholar</v-btn>
                  <v-btn large style="background-color: #171515" href="https://github.com/faroit"><v-icon left>fab fa-github</v-icon>Github</v-btn>
                  <v-btn large style="background-color: #ff0084" href="https://flickr.com/faroit"><v-icon left>fab fa-flickr</v-icon>Flickr</v-btn>
                </v-layout>
              </div>
            </v-flex>
          </v-layout>
        </v-parallax>

        </v-container>
      </v-content>
      <v-footer class="secondary" app>
        <v-layout row wrap align-center>
          <v-flex xs12>
            <div class="white--text ml-3">
              Made with
              <v-icon class="red--text">favorite</v-icon>
            </div>
          </v-flex>
        </v-layout>
      </v-footer>
  </v-app>
</template>

<script>
import VueMarkdown from 'vue-markdown'
export default {
  data () {
    return {
      title: 'Vuetify.js'
    }
  },
  name: 'App',
  components: {
    'vue-markdown': VueMarkdown
  }
}
</script>
