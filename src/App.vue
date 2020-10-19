<template>
  <div class="container mx-auto font-body">
    <Header />
    <p>Hola Mundo</p>
    <Footer />
  </div>
</template>

<script>
  import Footer from './components/footer'
  import Header from './components/header'

  export default {
    name: 'App',
    components: {
      Footer,
      Header
    }
  }
</script>