<template>
  <v-app id ="app">
      <v-navigation-drawer>
          <v-content>
            <v-container fluid>
               <router-view/>
            </v-container>
          </v-content>
      </v-navigation-drawer>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
