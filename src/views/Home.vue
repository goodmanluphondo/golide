<template>
  <div class="site">
    <SiteHeader />
    <SiteBanner />
    <div class="content">
      <p>This is the {{ projectName }} content.</p>
    </div>
    <SiteFooter />
  </div>
</template>
<style lang="scss">
@import "style/index.scss";
</style>
<script>
import SiteHeader from "@/components/SiteHeader.vue";
import SiteBanner from "@/components/SiteBanner.vue";
import SiteFooter from "@/components/SiteFooter.vue";
export default {
  name: "Home",
  components: {
    SiteHeader,
    SiteBanner,
    SiteFooter
  },
  computed: {
    projectName() {
      return this.$store.state.projectName;
    }
  }
};
</script>
