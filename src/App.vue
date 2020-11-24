<template>
  <div id="app">
    <top-header/>
    <Header/>
    <router-view/>
  </div>
</template>
<script>
import TopHeader from './components/TopHeader';
import Header from './components/Header';
export default {
  components: {
    TopHeader,
    Header
  }
}
</script>

