<template>
  <b-navbar class="container">
    <template #brand>
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <img src="~/assets/Ninja.svg" alt="Ninja Army Logo">
      </b-navbar-item>
    </template>
    <template #start>
      <b-navbar-item tag="router-link" :to="{ path: '/', hash:'#AboutMe'}" >
        About Me
      </b-navbar-item>
      <b-navbar-item tag="router-link" :to="{ path: '/', hash:'#Projects'}">
        Projects
      </b-navbar-item>
      <b-navbar-item tag="router-link" :to="{ path: '/', hash:'#mission'}">
        Mission
      </b-navbar-item>

    </template>

  </b-navbar>
</template>

<style lang="scss">
.navbar-brand {
  img {
    width: 100%;
  }
}
.navbar-item img {
  max-height: 2.75rem;
}

.navbar-menu {

  a:hover {
    color: #3db2ff;
  }


}

</style>
