<template>
  <footer>
    <p>
      Copyright &copy; {{ currentYear }}
      <a href="https://goodmanluphondo.com" target="_blank">{{ projectName }}</a
      >. All rights reserved.
    </p>
    <nav>
      <font-awesome-icon :icon="['fab', 'twitter']" />&nbsp;
      <a href="https://twitter.com/goodmanluphondo">goodmanluphondo</a> |
      <font-awesome-icon :icon="['fab', 'facebook-f']" />&nbsp;
      <a href="https://facebook.com/goodmanluphondo">goodmanluphondo</a> |
      <font-awesome-icon :icon="['fab', 'instagram']" />&nbsp;
      <a href="https://instagram.com/goodmanluphondo">goodmanluphondo</a> |
      <font-awesome-icon :icon="['fab', 'whatsapp']" /> +27 76 188 8182
    </nav>
  </footer>
</template>
<script>
export default {
  computed: {
    projectName() {
      return this.$store.state.projectName;
    },
    currentYear() {
      var dd = new Date();
      var yy = dd.getFullYear();

      return yy;
    }
  }
};
</script>
