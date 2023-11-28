<script>

import AppHeader from "./components/AppHeader.vue"
import AppContentMain from "./components/AppContentMain.vue"
import AppInfoMain from "./components/AppInfoMain.vue"
import AppMenuFooter from "./components/AppMenuFooter.vue"


export default {
  components: {
    AppHeader,
    AppContentMain,
    AppInfoMain,
    AppMenuFooter,
  }
}

</script>

<template>
  <AppHeader />
  <main>
    <AppContentMain />
    <AppInfoMain />
  </main>
  <AppMenuFooter />
</template>

<style scoped></style>
