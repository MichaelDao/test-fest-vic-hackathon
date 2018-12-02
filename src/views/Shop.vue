<template>
    <v-content>
        <v-container fluid>
            <v-layout row wrap>
            <v-flex xs12 sm6 md4>
                <v-card>
                    <!--image here-->
                    <v-img
                            :src="require('@/assets/atomo01.jpg')"
                            height="200px"
                    >
                    </v-img>

                    <v-card-title primary-title>
                        <div>
                            Atomo Diagnostics HIV Testing Kit
                        </div>
                    </v-card-title>

                    <v-card-text>
                        $TBA
                    </v-card-text>

                    <v-card-actions>
                        <!--<v-btn flat>Share</v-btn>-->
                        <v-btn style="left:42%" flat color="purple">Buy</v-btn>
                        <!--<v-spacer></v-spacer>
                            <v-btn icon @click="show = !show">
                                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
                            </v-btn>-->
                    </v-card-actions>
                </v-card>
            </v-flex>
                <v-flex xs12 sm6 md4>
                    <v-card>
                        <!--image here-->
                        <v-img
                                :src="require('@/assets/condomBundle.jpg')"
                                height="200px"
                        >
                        </v-img>

                        <v-card-title primary-title>
                            <div>
                                Bundle of Condoms

                            </div>
                        </v-card-title>

                        <v-card-text>
                            $7

                        </v-card-text>

                        <v-card-actions>
                            <!--<v-btn flat>Share</v-btn>-->
                            <v-btn style="left:42%" flat
                                   color="purple">Buy</v-btn>
                            <!--<v-spacer></v-spacer>
                            <v-btn icon @click="show = !show">
                                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
                            </v-btn>-->
                        </v-card-actions>
                    </v-card>
                </v-flex>
                <v-flex xs12 sm6 md4>
                    <v-card>
                        <!--image here-->
                        <v-img
                                :src="require('@/assets/durex.jpeg')"
                                height="200px"
                        >
                        </v-img>

                        <v-card-title primary-title>
                            <div>
                                2xPair Durex condoms

                            </div>
                        </v-card-title>

                        <v-card-text>
                            $5

                        </v-card-text>

                        <v-card-actions>
                            <!--<v-btn flat>Share</v-btn>-->
                            <v-btn to="./BuyModel" style="left:42%" flat
                                   color="purple">Buy
                            </v-btn>
                            <!--<v-spacer></v-spacer>
                            <v-btn icon @click="show = !show">
                                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
                            </v-btn>-->
                        </v-card-actions>
                    </v-card>
                </v-flex>
                <v-flex xs12 sm6 md4>
                    <v-card>
                        <!--image here-->
                        <v-img
                                :src="require('@/assets/femaleCondom.jpg')"
                                height="200px"
                        >
                        </v-img>

                        <v-card-title primary-title>
                            <div>
                                Female Condom

                            </div>
                        </v-card-title>

                        <v-card-text>
                           $18.50

                        </v-card-text>

                        <v-card-actions>
                            <!--<v-btn flat>Share</v-btn>-->
                            <v-btn style="left:42%" flat color="purple">Buy
                            </v-btn>
                            <!--<v-spacer></v-spacer>
                            <v-btn icon @click="show = !show">
                                <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
                            </v-btn>-->
                        </v-card-actions>
                    </v-card>
                </v-flex>

                    <v-btn fixed bottom right fab dark small color="primary">
                        <v-icon>add_shopping_cart</v-icon>
                    </v-btn>

            </v-layout>
        </v-container>
    </v-content>
</template>

<script>


    export default {
        name: "Shop",
        components: {

        }
    }
</script>

<style scoped>
    * {
        box-sizing: border-box;
    }


    body,template {
        height:100%;
        margin:0;
    }

    .header {
        text-align: center;
        padding: 32px;
    }

    /* Create two equal columns that floats next to each other */
    .column {
        width: 50%;
        background-color:white;
        padding: 10px;
    }

    .column img {
        margin-top: 12px;
    }

    /* Clear floats after the columns */
    .row:after {
        content: "";
        display: table;
        clear: both;
    }

    .center-items {
        position:absolute;
        margin-top:-1%;
        margin-left:28%;
    }

    .shop-title{
      left:28%;
      z-index:1;
      position:absolute;
    }
    .background-img {
      margin-top:10%;
      background-image:url('../assets/bokeh.jpg');
      background-repeat: no-repeat;
      background-position:center;
      background-size:cover;
      background-attachment:fixed;
      width:100%;
      height:100%;
      z-index:0;
    }

    /* The Modal (background) */
    .modal {
      display: none; /* Hidden by default */
      position: fixed; /* Stay in place */
      z-index: 1; /* Sit on top */
      padding-top: 100px; /* Location of the box */
      left: 0;
      top: 0;
      width: 100%; /* Full width */
      height: 100%; /* Full height */
      overflow: auto; /* Enable scroll if needed */
      background-color: rgb(0,0,0); /* Fallback color */
      background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
    }

    /* Modal Content */
    .modal-content {
      background-color: #fefefe;
      margin: auto;
      padding: 20px;
      border: 1px solid #888;
      width: 80%;
    }

    /* The Close Button */
    .close {
      color: #aaaaaa;
      float: right;
      font-size: 28px;
      font-weight: bold;
    }

    .close:hover,
    .close:focus {
      color: #000;
      text-decoration: none;
      cursor: pointer;
    }
</style>