<template>
    <div id="app">
        <v-app light>
            <!--<head>-->
                <!--<link href='https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700,900|Material+Icons'-->
                      <!--rel="stylesheet">-->
            <!--</head>-->

            <v-toolbar>
                <v-toolbar-side-icon></v-toolbar-side-icon>
                <router-link to="/"><img src="@/assets/logo.png"/></router-link>
                <v-spacer></v-spacer>
                <v-toolbar-items>
                    <v-btn flat to="/"><v-icon>mdi-house</v-icon>Home</v-btn>
                    <v-btn flat to="/about">Why</v-btn>
                    <v-btn flat to="/quiz">Quiz</v-btn>
                    <v-btn flat to="/shop">Shop</v-btn>
                </v-toolbar-items>
            </v-toolbar>

            <router-view/>
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
            return {
                //
            }
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
