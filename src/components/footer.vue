<template>
  <footer class="footer-footer" v-bind:class="rootClassName">
    <div class="footer-container">
      <img :src="imageSrc" :alt="imageAlt" class="footer-image" />
      <div class="footer-container1">
        <span class="footer-text">
          <span>© 2024 Oliver Burgess</span>
          <br />
          <span>All Rights Reserved.</span>
        </span>
        <div class="footer-icon-group">
          <a
            href="https://twitter.com/CHS_MUNCH"
            target="_blank"
            rel="noreferrer noopener"
            class="footer-link"
          >
            <svg viewBox="0 0 950.8571428571428 1024" class="footer-icon">
              <path
                d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
              ></path>
            </svg>
          </a>
          <a
            href="https://instagram.com/chs_munch23"
            target="_blank"
            rel="noreferrer noopener"
            class="footer-link1"
          >
            <svg viewBox="0 0 877.7142857142857 1024" class="footer-icon2">
              <path
                d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
              ></path>
            </svg>
          </a>
          <svg viewBox="0 0 602.2582857142856 1024" class="footer-icon4">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </div>
    <div class="footer-container2">
      <div class="footer-container3">
        <span class="footer-text04">{{ text }}</span>
        <span class="footer-text05">{{ text1 }}</span>
        <span class="footer-text06">{{ text2 }}</span>
        <span class="footer-text07">{{ text3 }}</span>
        <span>{{ text4 }}</span>
      </div>
      <div class="footer-container4">
        <span class="footer-text09">{{ text5 }}</span>
        <span class="footer-text10">{{ text6 }}</span>
        <span class="footer-text11">{{ text7 }}</span>
        <span class="footer-text12">{{ text8 }}</span>
        <span>{{ text9 }}</span>
      </div>
      <div class="footer-container5">
        <span class="footer-text14">{{ text10 }}</span>
        <span class="footer-text15">{{ text11 }}</span>
        <span class="footer-text16">{{ text12 }}</span>
        <span class="footer-text17">{{ text13 }}</span>
        <span>{{ text14 }}</span>
      </div>
      <div class="footer-container6">
        <span class="footer-text19">{{ text15 }}</span>
        <span class="footer-text20">{{ text16 }}</span>
        <span class="footer-text21">{{ text17 }}</span>
        <span class="footer-text22">{{ text18 }}</span>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    imageSrc: {
      type: String,
      default: '/munch_logo-200h.png',
    },
    imageAlt: {
      type: String,
      default: 'image',
    },
    text: {
      type: String,
      default: 'MUNCH 24',
    },
    text1: {
      type: String,
      default: 'Committees',
    },
    text2: {
      type: String,
      default: 'Timetable',
    },
    text3: {
      type: String,
      default: 'Country Allocation',
    },
    text4: {
      type: String,
      default: 'Briefing Papers',
    },
    text5: {
      type: String,
      default: 'People',
    },
    text6: {
      type: String,
      default: 'Officials',
    },
    text7: {
      type: String,
      default: 'Chairs',
    },
    text8: {
      type: String,
      default: 'Press',
    },
    text9: {
      type: String,
      default: 'Infrastructure\n',
    },
    text10: {
      type: String,
      default: 'Information',
    },
    text11: {
      type: String,
      default: 'Advisors',
    },
    text12: {
      type: String,
      default: 'Delegates',
    },
    text13: {
      type: String,
      default: 'Charity',
    },
    text14: String,
    text15: {
      type: String,
      default: 'Support',
    },
    text16: {
      type: String,
      default: 'Contact',
    },
    text17: {
      type: String,
      default: 'Privacy Policy',
    },
    text18: {
      type: String,
      default: 'Technical Support',
    },
    linkIcon: {
      type: String,
      default: 'https://twitter.com/CHS_MUNCH',
    },
    linkIcon1: {
      type: String,
      default: 'https://instagram.com/chs_munch23',
    },
    rootClassName: String,
  },
}
</script>

<style scoped>
.footer-footer {
  height: 224px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
}
.footer-container {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: space-between;
  padding-right: var(--dl-space-space-sixunits);
  flex-direction: column;
}
.footer-image {
  width: 200px;
  object-fit: cover;
}
.footer-container1 {
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: flex-start;
  flex-direction: column;
}
.footer-text {
  margin-top: var(--dl-space-space-oneandhalfunits);
}
.footer-icon-group {
  display: flex;
  margin-top: var(--dl-space-space-oneandhalfunits);
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.footer-link {
  display: contents;
}
.footer-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
  text-decoration: none;
}
.footer-link1 {
  display: contents;
}
.footer-icon2 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
  text-decoration: none;
}
.footer-icon4 {
  fill: #D9D9D9;
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.footer-container2 {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.footer-container3 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-sixunits);
  flex-direction: column;
  justify-content: flex-start;
}
.footer-text04 {
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.footer-text05 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-text06 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-text07 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-container4 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-sixunits);
  flex-direction: column;
  justify-content: flex-start;
}
.footer-text09 {
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.footer-text10 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-text11 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-text12 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-container5 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-sixunits);
  flex-direction: column;
  justify-content: flex-start;
}
.footer-text14 {
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.footer-text15 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-text16 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-text17 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-container6 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.footer-text19 {
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.footer-text20 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-text21 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-text22 {
  margin-bottom: var(--dl-space-space-unit);
}
.footer-root-class-name {
  top: 77.5%;
  left: 0px;
  right: 0px;
  width: var(--dl-size-size-maxwidth);
  height: 22.5%;
  position: absolute;
  max-width: var(--dl-size-size-maxwidth);
  margin-top: auto;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: auto;
}
@media(max-width: 991px) {
  .footer-footer {
    flex-direction: column;
  }
  .footer-container1 {
    align-items: center;
  }
}
@media(max-width: 767px) {
  .footer-footer {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .footer-container4 {
    margin-right: 0px;
  }
  .footer-container6 {
    margin-right: var(--dl-space-space-unit);
  }
}
@media(max-width: 479px) {
  .footer-footer {
    padding: var(--dl-space-space-unit);
  }
  .footer-container3 {
    margin-right: var(--dl-space-space-unit);
  }
  .footer-container4 {
    align-self: stretch;
  }
}
</style>
