<template>
  <div class="home-container">
    <div class="home-container1">
      <span class="home-text">MUNCH Website</span>
      <img
        alt="image"
        src="/image-removebg-preview-300h.png"
        class="home-image"
      />
      <div class="home-container2">
        <router-link to="/" class="home-navlink">People</router-link>
        <router-link to="/" class="home-navlink1">Home</router-link>
      </div>
      <div class="home-container3">
        <div class="home-container4">
          <img alt="image" src="/munch_logo2-200h.png" class="home-image1" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
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
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-container1 {
  flex: 0 0 auto;
  width: 100%;
  height: var(--dl-size-size-xxlarge);
  display: flex;
  opacity: 1;
  position: relative;
  align-items: center;
  background-size: cover;
  justify-content: center;
  background-image: url("/flag-banner_edited-1-1500w.jpg");
}
.home-text {
  top: var(--dl-space-space-oneandhalfunits);
  left: var(--dl-space-space-sixunits);
  color: var(--dl-color-gray-black);
  position: absolute;
  font-size: 32px;
  text-align: left;
  font-family: "Source Sans 3";
}
.home-image {
  top: var(--dl-space-space-unit);
  left: var(--dl-space-space-unit);
  width: 64px;
  opacity: 1;
  position: absolute;
  object-fit: cover;
}
.home-container2 {
  top: 0px;
  flex: 0 0 auto;
  right: 0px;
  width: 75%;
  height: var(--dl-size-size-medium);
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.home-navlink {
  top: var(--dl-space-space-oneandhalfunits);
  left: 640px;
  color: var(--dl-color-gray-black);
  margin: auto;
  position: absolute;
  font-size: 24px;
  font-family: "Source Sans 3";
  text-decoration: none;
}
.home-navlink1 {
  top: var(--dl-space-space-oneandhalfunits);
  left: 512px;
  color: var(--dl-color-gray-black);
  margin: auto;
  position: absolute;
  font-size: 24px;
  font-family: "Source Sans 3";
  text-decoration: none;
}
.home-container3 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.home-container4 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.home-image1 {
  top: var(--dl-space-space-twounits);
  left: 0px;
  right: 0px;
  width: 40%;
  bottom: 0px;
  margin: auto;
  position: absolute;
  object-fit: cover;
}
@media(max-width: 1200px) {
  .home-container2 {
    height: 64px;
  }
  .home-image1 {
    top: var(--dl-space-space-twounits);
    width: 50%;
  }
}
</style>
