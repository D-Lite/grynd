<template>
<main class="bg-black">
  <div class="content pt-5 pb-0 px-20 py-20">
    <Header />
    <Page />
    <Footer />
  </div>
</main>
</template>

<script>
import Header from './components/Header'
import Page from './components/Page'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Page,
    Footer

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-family: 'Oswald', sans-serif;
}

main {
  min-height: 100vh;
  font-family: 'Oswald', sans-serif;
}

</style>
