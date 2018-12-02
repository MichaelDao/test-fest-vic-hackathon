<template>
    <div id="app">
        <v-app light>
            <head>
                <link href='https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700,900|Material+Icons'
                      rel="stylesheet">
                <link rel="stylesheet" href="https://unpkg.com/leaflet@1.3.4/dist/leaflet.css"
                      integrity="sha512-puBpdR0798OZvTTbP4A8Ix/l+A4dHDD0DGqYW6RQ+9jxkRFclaxxQb/SJAWZfWAkuyeQUytO7+7N4QKrDh+drA=="
                      crossorigin=""/>
            </head>

            <v-toolbar>
                <v-toolbar-side-icon>
                    <router-link to="/"><img height="40px" width="40px" :src="require('@/assets/icons/logo.svg')"
                                             alt="logo"/>
                    </router-link>
                </v-toolbar-side-icon>

                <!--<v-btn to="/"></v-btn>-->
                <!--<v-toolbar-side-icon><router-link to="/"><img src="@/assets/icons/TranBg3.svg" /></router-link></v-toolbar-side-icon>-->
                <v-spacer></v-spacer>
                <v-toolbar-items>
                    <v-btn flat to="/">
                        <v-icon>home</v-icon>
                    </v-btn>
                    <v-btn flat to="/about">
                        <v-icon>account_box</v-icon>
                    </v-btn>
                    <v-btn flat to="/quiz">
                        <v-icon>question_answer</v-icon>
                    </v-btn>
                    <v-btn flat to="/shop">
                        <v-icon>shopping_cart</v-icon>
                        </v-btn>
                </v-toolbar-items>
            </v-toolbar>
            <!--for different router view-->
            <v-content>
                <router-view/>
            </v-content>

            <!--footer-->
            <v-footer class="blue darken-2">
                <v-layout row wrap align-center>
                    <v-flex xs12>
                        <div class="white--text ml-3">
                            Made with
                            <v-icon class="red--text">mdi-cards-heart</v-icon>
                            by <a class="white--text" href="https://vuetifyjs.com" target="_blank">OneDrop</a>
                        </div>
                    </v-flex>
                </v-layout>
            </v-footer>
        </v-app>
    </div>
</template>

<script>
    import Vue from 'vue';
    import Vuetify from 'vuetify';
    import 'vuetify/dist/vuetify.min.css'; // Ensure you are using css-loader

    Vue.use(Vuetify);

    export default {
        name: 'App',
        components: {},
        data() {
            return {}
        }
    }

</script>

<style lang="scss">
    #app {
        font-family: "Avenir", Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }

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