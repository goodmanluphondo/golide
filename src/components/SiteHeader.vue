<template>
  <header>
    <div class="header">
      <div class="header__socials">
        <div>7 Smith Street, Some City 0102</div>
        <nav>
          <a href="https://twitter.com/goodmanluphondo" target="_blank"
            ><font-awesome-icon :icon="['fab', 'twitter']"
          /></a>
          <a href="https://facebook.com/goodmanluphondo" target="_blank"
            ><font-awesome-icon :icon="['fab', 'facebook']"
          /></a>
          <a href="https://instagram.com/goodmanluphondo" target="_blank"
            ><font-awesome-icon :icon="['fab', 'instagram']"
          /></a>
        </nav>
      </div>
      <div class="header__menu">
        <div class="logo">
          <router-link to="/"><h1>Logo</h1></router-link>
        </div>
        <div class="menu">
          <nav>
            <router-link to="/">Home</router-link>
            <router-link to="/services">Services</router-link>
            <router-link to="/contact">Contact</router-link>
          </nav>
        </div>
      </div>
    </div>
  </header>
</template>
<style lang="scss">
.header {
  width: 100%;

  .header__socials {
    width: 100%;
    height: 50px;
    line-height: 50px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    background: gray;
    padding: 0px 10px;
  }
  .header__menu {
    width: 100%;
    height: 50px;
    line-height: 50px;
    display: flex;
    padding: 0px 10px;

    .logo {
      width: 200px;
    }
    .menu {
      width: calc(100% - 200px);

      nav {
        width: 100%;
        display: flex;
        flex-direction: row;
        justify-content: right;
      }
    }
  }
}
</style>
