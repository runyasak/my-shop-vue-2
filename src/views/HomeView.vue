<script lang="ts" setup>
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import { SfImage } from '@storefront-ui/vue';
</script>

<template>
  <div class="home">
    <SfImage
      src="https://picsum.photos/300/300"
      alt="Vila stripe maxi shirt dress"
      :width="null"
      :height="null"
    />
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>
