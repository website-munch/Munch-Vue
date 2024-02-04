<template>
  <div class="home-container">
    <div class="home-container1">
      <app-header rootClassName="header-root-class-name"></app-header>
      <div class="home-container2">
        <div class="home-feature-card">
          <span class="home-text">
            <span>We are looking forward to having you at MUNCH 24. </span>
            <span>It will take place on Saturday 5th - Sunday 6th October.</span>
            <br />
            <span>We will send out formal invitations in mid-March. </span>
            <span>
              Please
              <span v-html="rawum4c"></span>
            </span>
            <a
              href="mailto:munch@chschool.co.uk?subject=MUNCH 24 New School"
              class="home-link"
            >
              contact us
            </a>
            <span>if you have not been before.</span>
            <br />
            <br />
            <span>
              Since 2001, Cheadle Hulme School has been proud to host an annual
              MUN conference and we hope that you will enjoy our 24th conference.
            </span>
            <br />
            <br />
            <span>
              Model United Nations is one of the few opportunities for truly
              independent study and for students to gain vital skills for their
              future. Students learn about countries around the world, acquire the
              ability to state an idea clearly and build consensus to find
              solutions to the global problems that will affect them in later
              life.
            </span>
            <br />
            <br />
            <span>
              In addition to this, MUNCH provides the opportunity to meet people
              from all over the UK and Europe in a very welcoming environment with
              a very high standard of debate and opportunities for delegates of
              all levels of experience.
            </span>
            <br />
            <br />
            <span>
              The Secretary General for this conference will be Sam Barnett and on
              behalf of everyone here at Cheadle Hulme School, we wish you happy
              and fruitful debating!
            </span>
            <br />
          </span>
        </div>
        <div class="home-feature-card1">
          <span class="home-text20">
            <span>MUNCH 24 Timeline</span>
            <br />
            <br />
            <span>March - Formal invitations sent out</span>
            <br />
            <span>May - Country allocations sent out</span>
            <br />
            <span>June - Guest chair application deadline</span>
            <br />
            <span>July - Briefing papers published</span>
            <br />
            <span>September - Forms B + C deadline</span>
            <br />
            <span>3rd October - Resolutions deadline</span>
            <br />
            <span>5th-6th October - MUNCH 24 in session</span>
          </span>
        </div>
      </div>
    </div>
    <app-footer
      rootClassName="footer-root-class-name"
      imageSrc="/munch_logo-200h.png"
    ></app-footer>
  </div>
</template>

<script>
import AppHeader from '../components/header'
import AppFooter from '../components/footer'

export default {
  name: 'Home',
  props: {},
  components: {
    AppHeader,
    AppFooter,
  },
  data() {
    return {
      rawum4c: ' ',
    }
  },
  metaInfo: {
    title: 'Munch',
    meta: [
      {
        property: 'og:title',
        content: 'Munch',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  position: relative;
  min-height: 100vh;
  background-color: #ffffe6;
}
.home-container1 {
  width: 100%;
  display: flex;
  min-height: 100vh;
}
.home-container2 {
  flex: 0 0 auto;
  width: 100%;
  height: 50%;
  display: flex;
  margin-top: 7.5%;
  align-items: flex-start;
  padding-left: 128px;
  padding-bottom: 64px;
}
.home-feature-card {
  top: 144px;
  float: left;
  width: 60%;
  height: 512px;
  padding: var(--dl-space-space-twounits);
  align-items: center;
}
.home-text {
  color: var(--dl-color-gray-black);
  align-self: flex-start;
  text-align: left;
  line-height: 1.75;
}
.home-link {
  font-style: normal;
  font-weight: 600;
}
.home-feature-card1 {
  top: 144px;
  width: 40%;
  margin: 0px;
  padding: var(--dl-space-space-twounits);
  align-items: center;
}
.home-text20 {
  color: var(--dl-color-gray-black);
  align-self: flex-start;
  text-align: left;
  line-height: 1.75;
}
</style>
