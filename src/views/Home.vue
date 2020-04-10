<template>
  <div>
    <NavBar/>
    <Content/>
    <Footer/>
  </div>

</template>

<script>
import NavBar from '@/components/NavBar.vue';
import Content from '@/components/Content.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'Home',
  components: {
    NavBar, Content, Footer,
  },
};
</script>