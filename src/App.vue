<template>
 <v-app>
   <v-navigation-drawer app>hi</v-navigation-drawer>
   <v-toolbar app>hello</v-toolbar>
   <v-content>
     <v-container fluid>
       <router-view>pep</router-view>
     </v-container>
   </v-content>
   <v-footer app>noh</v-footer>
 </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
