<template>
  <header v-once>
    <div class="buttons">

    </div>

    <NavMenu />

    <div class="buttons">

    </div>
  </header>
</template>

<script setup lang="ts">

</script>

<style scoped>
header {
  width: 100%;
}

div .buttons {
  min-width: 33%;
  width: 33%;
}

nav {
  width: 34%;
}

a {
  color: var(--header-link)
}
</style>