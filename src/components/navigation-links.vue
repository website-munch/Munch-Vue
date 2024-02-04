<template>
  <nav class="navigation-links-nav" v-bind:class="rootClassName">
    <span class="navigation-links-text">{{ text0 }}</span>
    <span class="navigation-links-text1">{{ text1 }}</span>
    <span class="navigation-links-text2">{{ text2 }}</span>
    <span class="navigation-links-text3">{{ text3 }}</span>
  </nav>
</template>

<script>
export default {
  name: 'NavigationLinks',
  props: {
    text0: {
      type: String,
      default: 'MUNCH24',
    },
    text3: {
      type: String,
      default: 'Support',
    },
    text1: {
      type: String,
      default: 'People',
    },
    rootClassName: String,
    text2: {
      type: String,
      default: 'Information',
    },
  },
}
</script>

<style scoped>
.navigation-links-nav {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.navigation-links-text1 {
  margin-left: var(--dl-space-space-twounits);
}
.navigation-links-text2 {
  margin-left: var(--dl-space-space-twounits);
}
.navigation-links-text3 {
  margin-left: var(--dl-space-space-twounits);
}








.navigation-links-root-class-name19 {
  margin-top: var(--dl-space-space-unit);
}
@media(max-width: 767px) {
  .navigation-links-nav {
    align-items: flex-start;
    flex-direction: column;
  }
  .navigation-links-text {
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text1 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text2 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text3 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
}
</style>
