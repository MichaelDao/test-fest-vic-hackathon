<template>
    <div class="home">
        <v-container fluid>
                <section>
                    <v-parallax :src="require('@/assets/hero.jpeg')" height="600">
                        <v-layout
                                column
                                align-center
                                justify-center
                                class="white--text"
                        >
                            <div class="bg-dark-img">
                            <img :src="require('@/assets/icons/TranBg1.svg')" alt="Vuetify.js" height="200">
                            </div>
                            <h1 class="white--text mb-2 display-1 text-xs-center">Get tested for HIV for free!</h1>
                            <!--<div class="subheading mb-3 text-xs-center"></div>-->
                            <!--<v-btn-->
                                    <!--class="blue lighten-2 mt-5"-->
                                    <!--dark-->
                                    <!--large-->
                                    <!--href="/pre-made-themes"-->
                            <!--&gt;-->
                                <!--Get Started-->
                            <!--</v-btn>-->

                        </v-layout>
                    </v-parallax>
                </section>

                <section>
                    <v-layout
                        column
                        wrap
                        class="my-5"
                        align-center
                        >
                        <v-flex xs12 sm6 md6 class="my-3">
                            <h2 class="headline">HIV Testing Kit</h2>
                            <span class="subheading">Get a free HIV Testing Kit today! </span>
                            <p>When you complete the quiz, you can get a free HIV testing kit delivered to your house or at any of our vending machine at convenient locations around Australia!</p>
                        </v-flex>
                        <v-flex xs12 sm6 md6 class="my-3">
                            <div id="map">

                            </div>
                        </v-flex>
                    </v-layout>
                    <v-layout
                        row
                        wrap
                        class="my-5"
                        align-center
                    >
                        <v-flex xs-12 md-12>
                            <h1>Benefits of HIV Testing</h1>
                        </v-flex>
                    </v-layout>
                    <v-layout
                            column
                            wrap
                            class="my-5"
                            align-center
                    >


                        <v-flex xs12>
                            <v-container grid-list-xl>
                                <v-layout row wrap align-center>
                                    <v-flex xs12 md3>
                                        <v-card class="elevation-0 transparent">
                                            <v-card-text class="text-xs-center">
                                                <v-icon x-large class="blue--text text--lighten-2">color_lens</v-icon>
                                            </v-card-text>
                                            <v-card-title primary-title class="layout justify-center">
                                                <div class="headline text-xs-center">Early detection</div>
                                            </v-card-title>
                                            <v-card-text>
                                                Early detection is the key to slowing the spread of HIV
                                            </v-card-text>
                                        </v-card>
                                    </v-flex>
                                    <v-flex xs12 md3>
                                        <v-card class="elevation-0 transparent">
                                            <v-card-text class="text-xs-center">
                                                <v-icon x-large class="blue--text text--lighten-2">flash_on</v-icon>
                                            </v-card-text>
                                            <v-card-title primary-title class="layout justify-center">
                                                <div class="headline">Less likely to transmit disease</div>
                                            </v-card-title>
                                            <v-card-text>
                                                HIV positive people who KNOW their status are <strong>less likely</strong> to transmit the virus to someone else.
                                            </v-card-text>
                                        </v-card>
                                    </v-flex>
                                    <v-flex xs12 md3>
                                        <v-card class="elevation-0 transparent">
                                            <v-card-text class="text-xs-center">
                                                <v-icon x-large class="blue--text text--lighten-2">build</v-icon>
                                            </v-card-text>
                                            <v-card-title primary-title class="layout justify-center">
                                                <div class="headline text-xs-center">Fight HIV</div>
                                            </v-card-title>
                                            <v-card-text>
                                                Early detection allows for the HIV positive person to receive anti-HIV medications to fight the HIV
                                            </v-card-text>
                                        </v-card>
                                    </v-flex>
                                    <v-flex xs12 md3>
                                        <v-card class="elevation-0 transparent">
                                            <v-card-text class="text-xs-center">
                                                <v-icon x-large class="blue--text text--lighten-2">build</v-icon>
                                            </v-card-text>
                                            <v-card-title primary-title class="layout justify-center">
                                                <div class="headline text-xs-center">Longer-term survival</div>
                                            </v-card-title>
                                            <v-card-text>
                                                Earlier treatment is the key to longer-term survival and higher CD4 levels.
                                            </v-card-text>
                                        </v-card>
                                    </v-flex>
                                </v-layout>
                            </v-container>
                        </v-flex>
                    </v-layout>
                </section>

                <section>
                    <v-parallax :src="require('@/assets/section.jpg')" height="380">
                        <v-layout column align-center justify-center>
                            <div class="headline white--text mb-3 text-xs-center">Web development has never been
                                easier
                            </div>
                            <em>Kick-start your application today</em>
                            <v-btn
                                    class="blue lighten-2 mt-5"
                                    dark
                                    large
                                    href="/pre-made-themes"
                            >
                                Get Started
                            </v-btn>
                        </v-layout>
                    </v-parallax>
                </section>

                <section>
                    <v-container grid-list-xl>
                        <v-layout row wrap justify-center class="my-5">
                            <v-flex xs12 sm4>
                                <v-card class="elevation-0 transparent">
                                    <v-card-title primary-title class="layout justify-center">
                                        <div class="headline">Company info</div>
                                    </v-card-title>
                                    <v-card-text>
                                        <p>We are a startup focus on providing essential HIV testing to at risk people living in Australia completely free!</p>
                                    </v-card-text>
                                </v-card>
                            </v-flex>
                            <v-flex xs12 sm4 offset-sm1>
                                <v-card class="elevation-0 transparent">
                                    <v-card-title primary-title class="layout justify-center">
                                        <div class="headline">Contact us</div>
                                    </v-card-title>
                                    <v-card-text>

                                    </v-card-text>
                                    <v-list class="transparent">
                                        <v-list-tile>
                                            <v-list-tile-action>
                                                <v-icon class="blue--text text--lighten-2">phone</v-icon>
                                            </v-list-tile-action>
                                            <v-list-tile-content>
                                                <v-list-tile-title>1800 659 547</v-list-tile-title>
                                            </v-list-tile-content>
                                        </v-list-tile>
                                        <v-list-tile>
                                            <v-list-tile-action>
                                                <v-icon class="blue--text text--lighten-2">place</v-icon>
                                            </v-list-tile-action>
                                            <v-list-tile-content>
                                                <v-list-tile-title>1 Londale Street, Melbourne 3000, Victoria, Australia</v-list-tile-title>
                                            </v-list-tile-content>
                                        </v-list-tile>
                                        <v-list-tile>
                                            <v-list-tile-action>
                                                <v-icon class="blue--text text--lighten-2">email</v-icon>
                                            </v-list-tile-action>
                                            <v-list-tile-content>
                                                <v-list-tile-title>ceo@onedrop.com</v-list-tile-title>
                                            </v-list-tile-content>
                                        </v-list-tile>
                                    </v-list>
                                </v-card>
                            </v-flex>
                        </v-layout>
                    </v-container>
                </section>


        </v-container>
    </div>

</template>

<script>
import L from 'leaflet';

    export default {
        name: "Home",
        components: {},
        mounted: function(){
            let mymap = L.map('map').setView([-37.8001008, 144.95825360000003], 13);
            L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', {
                attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, <a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
                maxZoom: 18,
                id: 'mapbox.streets',
                accessToken: 'pk.eyJ1Ijoid2lsc29ubXVuIiwiYSI6ImNqcDU2eGxoajEwZnEzcXMwb3g0MDV1dXkifQ.z9rSU-J-ZLBpjh5cSsbJng'
            }).addTo(mymap);

            //add marker to map, peter institute
            L.markers([-37.800224, 144.958295]).addTo(mymap);
            //healthsmart chemist
            L.markers([-37.798817, 144.955548]).addTo(mymap);
            //melbourne central pharmacy
            L.markers([-37.809833, 144.963583]).addTo(mymap);

        },
        data(){
            return{

            }
        }
    };
</script>

<style scoped>
    .bg-dark-img {
        width: inherit;
        height: inherit;
        background-color: rgba(0,0,0,0.4);
        z-index: 100;
    }

    #map{
        height: 600px;
        width: 1000px;
    }
</style>
