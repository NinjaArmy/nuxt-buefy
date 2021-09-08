<template>
  <footer class="footer">
    <div class="content has-text-centered">
      <NuxtLink to="/Imprint">
        Imprint
      </NuxtLink>

    </div>
  </footer>
</template>

<script>
export default {
name: "Footer"
}
</script>

<style lang="scss">
.footer {
  padding: 1rem;

  a:hover {
    color: #3db2ff;
  }

  a:visited {
    color: #268df0;
  }
}

</style>
