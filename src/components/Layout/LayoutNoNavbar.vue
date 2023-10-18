<template>
    <AppHeader />
    <div>
      <slot class="content"><h2>Phần nội dung</h2></slot>
    </div>
  </template>
  
  <script>
  import AppHeader from '../AppHeader.vue'
  export default {
      name: 'LayoutNoNavbar',
      components: {
          AppHeader
      }
  }
  </script>
  
  <style>
  
  </style>