<template>
  <v-container grid-list-md text-xs-center>
    <v-layout row wrap>
      <v-flex xs12>
        <v-parallax
          light
          :src="require('../assets/pawel-czerwinski-1359427-unsplash.jpg')"
        >
          <v-layout align-center column justify-center>
            <v-avatar size="200px">
              <v-img :src="require('../assets/face.jpg')" class="my-3"></v-img>
            </v-avatar>
            <h1 class="display-2 font-weight-thin ma-3">Chris Hartgerink</h1>
            <h4 class="subheading">superb procrastinator</h4>
            <h2 class="subheading">
              <a href="mailto:chris@libscie.org"
                >write me if you think i can help you</a
              >
            </h2>
          </v-layout>
        </v-parallax>
      </v-flex>
      <v-flex xs12>
        <v-parallax
          :src="require('../assets/pawel-czerwinski-1424194-unsplash.jpg')"
          height="1000px"
        >
          <h2 class="display-2 font-weight-thick mt-3">About</h2>
          <v-responsive max-width="500px">
            <div class="body-2 ma-3">
              <p>
                Currently I work half-time at the
                <a href="https://quest.bihealth.org/"
                  >QUEST Center, Charité Medical Center</a
                >
                in Berlin. In the other half-time, I am starting
                <a href="https://libscie.org" target="_blank"
                  >Liberate Science</a
                >
                as a worker co-operative.
              </p>
              <p>
                I don't really like taking myself seriously, but I do take the
                issues I work on seriously. These include improving the
                reproducibility of scholarly research, an open Web, alternative
                business models (e.g., worker co-ops), and empathic design of
                our institutions.
              </p>
              <p>
                I don't really enjoy talking about myself on here either. Take a
                look at my online profile pages if you want to know what's going
                on and get in touch if you want to talk to a nerdy researcher
                who cares deeply about improving the systems that stab us in the
                back. Worst case scenario I will send you a nice reply; best
                case scenario we end up becoming friends in action.
              </p>
              <p class="d-flex">
                <a href="https://twitter.com/chartgerink">
                  <v-img
                    :src="require('../assets/noun_Twitter_2329673_FFFFFF.png')"
                    max-height="40px"
                    contain="true"
                    alt="Twitter"
                  ></v-img
                ></a>
                <!-- <a href="/assets/cv.pdf"> -->
                <!--   <v-img -->
                <!--     :src="require('../assets/noun_Chuvash_1044177.png')" -->
                <!--     max-height="40px" -->
                <!--     contain="true" -->
                <!--     alt="Twitter" -->
                <!--   ></v-img -->
                <!--      ></a> -->
                <a
                  href="https://scholar.google.de/citations?hl=en&user=FjH-BUcAAAAJ&view_op=list_works&sortby=pubdate"
                >
                  <v-img
                    :src="require('../assets/noun_scholar_1199156.png')"
                    max-height="40px"
                    contain="true"
                    alt="Google Scholar"
                  ></v-img
                ></a>

                <a href="https://github.com/chartgerink">
                  <v-img
                    :src="require('../assets/noun_code_1398972_FFFFFF.png')"
                    max-height="40px"
                    contain="true"
                    alt="GitHub"
                  ></v-img
                ></a>
                <a href="https://medium.com/@chartgerink">
                  <v-img
                    :src="require('../assets/noun_write_794738_FFFFFF.png')"
                    max-height="40px"
                    contain="true"
                    alt="Blog"
                  ></v-img
                ></a>
                <a href="mailto:chris@libscie.org">
                  <v-img
                    :src="require('../assets/noun_Email_2334165_FFFFFF.png')"
                    max-height="40px"
                    contain="true"
                    alt="Email me"
                  ></v-img>
                </a>
              </p>
            </div>
          </v-responsive>
        </v-parallax>
      </v-flex>
      <v-flex xs12 p6>
        <v-parallax :src="require('../assets/jason-leung-479251-unsplash.jpg')">
          <h2 class="display-2 font-weight-thin pa-3">(Previous) funders</h2>
          <p class="d-flex ma-5">
            <v-img
              :src="require('../assets/mozilla-logo-bw-rgb.png')"
              max-height="70px"
              contain="true"
            ></v-img>
            <v-img
              :src="require('../assets/shuttleworth_trans.png')"
              max-height="70px"
              contain="true"
            ></v-img>
          </p>
          <p class="d-flex ma-5">
            <v-img
              :src="require('../assets/ori-logo-black-bg.jpg')"
              max-height="70px"
              contain="true"
            ></v-img>
          </p>
        </v-parallax>
      </v-flex>
    </v-layout>
  </v-container>
</template>
