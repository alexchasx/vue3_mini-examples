<template>
  <app-header />
  <app-content />
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppContent from './components/AppContent.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppContent,
  },
};
</script>
