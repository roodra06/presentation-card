<template>
  <div class="about">
    <h1>This is an about page</h1>
    <HelloWorld></HelloWorld>
  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/Likes.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
  },
};
</script>
