<template>
    <nuxt-link :to="$route.query.back || '/'" class="text-blue-500">
      <Icon name="bi:chevron-left" /> Back
    </nuxt-link>
  </template>
  
  
  <script>
  export default {
    name: 'BackButton',
  }
  </script>
  