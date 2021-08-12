<template>
  <v-app>
    <SlideBar/>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
  import SlideBar from './components/SlideBar.vue'
  
export default {
  name: 'App',
  components: {
    SlideBar
  },

  data: () => ({
    //
  }),
};
</script>
