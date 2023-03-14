<script lang="ts">
import { defineComponent } from 'vue';
import HeaderView from './components/HeaderView.vue';
import HeroView from './components/HeroView.vue';
export default defineComponent({
  components: {
    HeaderView,
    HeroView,
  },
});
</script>

<template>
  <main class="hidden md:block">
    <HeaderView />
    <HeroView />
  </main>
</template>

<style>
main {
  background: #F5F5F5;
  min-height: 100vh;
  font-family: 'SF Pro Text';
}

html {
  height: 100%;
}

@font-face {
  font-family: 'SF Pro Text';
  src: local('SF Pro Text'),
    url(./fonts/SF-Pro-Text-Regular.otf)format('truetype');
}
</style>
