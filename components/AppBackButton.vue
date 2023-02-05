<template>
    <nuxt-link :to="$route.query.back || '/'" class="text-[#136FFB]">
      <Icon name="bi:chevron-left" /> Back
    </nuxt-link>
  </template>
  
  
  <script>
  export default {
    name: 'BackButton',
  }
  </script>
  