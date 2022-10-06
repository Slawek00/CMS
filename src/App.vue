<template>
  <AppMenu/>
  <AppLogin/>
  <AppFooter/>
</template>

<script>
import AppMenu from "@/components/AppMenu.vue";
import AppLogin from "@/components/AppLogin.vue"
import AppFooter from "@/components/AppFooter.vue";

export default {
  name: 'App',
  components:{
    AppMenu,
    AppLogin,
    AppFooter
  }
}

</script>

<style>

</style>
