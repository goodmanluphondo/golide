<template>
  <div class="site">
    <SiteHeader />
    <PageTitle title="Contact" />
    <div class="content">
      <p>This is the contact page.</p>
    </div>
    <SiteFooter />
  </div>
</template>
<style lang="scss">
@import "style/index.scss";
</style>
<script>
import PageTitle from "@/components/PageTitle.vue";
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
