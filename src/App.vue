<template>
  <my-header></my-header>
  <tab></tab>
  <router-view />
</template>

<script>
import Header from '@/components/header/header.vue';
import Tab from '@/components/tab/tab.vue';
export default {
  components: {
    myHeader: Header,
    Tab,
  },
};
</script>
