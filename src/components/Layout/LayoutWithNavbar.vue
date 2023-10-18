<template>
  <AppHeader />
  <div>
    <AppNavbar/>
    <slot></slot>
  </div>
</template>

<script>
import AppHeader from '../AppHeader.vue'
import AppNavbar from '../AppNavbar.vue'
export default {
    name: 'LayoutWithNavbar',
    components: {
        AppHeader,
        AppNavbar
    }
}
</script>

<style>

</style>