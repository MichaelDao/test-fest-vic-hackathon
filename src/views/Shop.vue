<template>
    <div class ="center-items">
        <div class="row">
            <div class ="column">
                <img src="@/assets/atomo01.jpg" style="width:50%">
                <img src="@/assets/durex.jpeg" style="width:50%">
                <img src="@/assets/femaleCondom.jpg" style="width:50%">
                <img src="@/assets/condomBundle.jpg" style="width:50%">
            </div>
        </div>
    </div>
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

    body {
        margin: 0;
        font-family: Arial;
    }

    .header {
        text-align: center;
        padding: 32px;
    }

    /* Create two equal columns that floats next to each other */
    .column {
        float: left;
        width: 50%;
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
        position:relative;
        left: 25%
    }
</style>