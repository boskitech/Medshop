<template>
  <v-app>
      <Header/>
      <Body />
      <Footer />
  </v-app>
</template>

<script>
import Header from './components/Header';
import Body from './components/Body';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    Header,
    Body,
    Footer
  },
    Footerata: () => ({
    //
  }),
};
</script>
