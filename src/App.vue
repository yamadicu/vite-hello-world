<script>
import AppTitle from './components/AppTitle.vue';
import Jumbotrone from './components/Jumbotrone.vue';

export default {
  name: "App",
  components: {
    AppTitle,
    Jumbotrone
  }
}
</script>

<template>
  <div>
    <AppTitle />
    <Jumbotrone />
  </div>
</template>

<style></style>
