<template>
  <div>
    <x-header id="header"/>
    <nuxt/>
    <x-footer id="footer"/>
  </div>
</template>

<script>
import { Header, Footer } from '@/components'

export default {
  components: {
    'x-header': Header,
    'x-footer': Footer,
  }
}
</script>

<style>
html{
  font-family: 'Helvetica Neue', 'Helvetica', sans-serif

}
  html, body, #header, #footer, #main {
    margin: 0;
    padding: 0;
  }
</style>
