<template>
  <v-app>
    <AppTopBar/>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

import AppTopBar from './components/shared/AppTopBar'

export default {
  name: 'App',

  components: {
    AppTopBar,
    
  },

};
</script>



#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
