<template>
  <Layout>
    {{message}}
  </Layout>
</template>

<script>
import Component from 'vue-class-component';
import Vue from 'vue';

@Component
export default class Index extends Vue {
  message = 'Index page'
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
