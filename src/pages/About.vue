<template>
  <Layout>
    {{message}}
  </Layout>
</template>

<script>
import Component from 'vue-class-component';
import Vue from 'vue';

@Component
export default class About extends Vue {
  message = 'About page'
}
</script>
