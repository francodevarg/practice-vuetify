<template>
  <v-app>
    <navbar/>
    
    <v-main>
      <v-container fluid>
        <router-view/>
      </v-container>
    </v-main>
    
  </v-app>
</template>

<script>
import { Navbar } from "./components";

export default {
  name: 'App',
  components:{
    Navbar
  },
  data: () => ({
    //
  }),
};
</script>
