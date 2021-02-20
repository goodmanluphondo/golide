<template>
  <div class="site">
    <SiteHeader />
    <PageTitle title="Services" />
    <div class="content">
      <p>This is the services page.</p>
    </div>
    <SiteFooter />
  </div>
</template>
<style lang="scss">
@import "style/index.scss";
</style>
<script>
import PageTitle from "@/components/PageTitle";
import SiteHeader from "@/components/SiteHeader.vue";
import SiteFooter from "@/components/SiteFooter.vue";
export default {
  name: "Home",
  components: {
    PageTitle,
    SiteHeader,
    SiteFooter
  }
};
</script>
