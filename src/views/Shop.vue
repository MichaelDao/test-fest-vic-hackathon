<template>
    <v-content>
        <v-container>
          <div style = "float:right;">
            <!-- Make this modal-->
              <img src = "@/assets/shopping_cart_full.png" style="width:30%">
          </div>
          <div class = "shop-title">
            <div>
              <img src = "@/assets/shoppingbag.jpg" style="width:20%">
            </div>
            <h1>One Drop Shop</h1>
          </div>
        </v-container>
        <v-container class = "background-img">
          <div class ="center-items">
            <div class="row">
              <div class ="column">
                <img src="@/assets/atomo01.jpg" style="width:50%">
                <img src="@/assets/durex.jpeg" style="width:50%">
              </div>
              <div class ="column">
                <img src="@/assets/femaleCondom.jpg" style="width:50%">
                <img src="@/assets/condomBundle.jpg" style="width:50%">
              </div>
            </div>
          </div>
        </v-container>
    </v-content>
</template>

<script>
    export default {
        name: "Shop"
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