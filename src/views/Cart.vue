<template>
    <v-container>
        <v-layout
            row
            wrap
        >
            <v-flex xs12 sm12 md12>
            <v-data-table
                    :headers="headers"
                    :items="desserts"
                    class="elevation-1"
            >
                <template slot="items" slot-scope="props">
                    <td>{{ props.item.name }}</td>
                    <td class="text-xs-right">{{ props.item.calories }}</td>
                    <td class="text-xs-right">{{ props.item.fat }}</td>
                    <td class="text-xs-right">{{ props.item.carbs }}</td>
                    <td class="text-xs-right">{{ props.item.protein }}</td>
                    <td class="text-xs-right">{{ props.item.iron }}</td>
                </template>
            </v-data-table>
            </v-flex>
        </v-layout>
    </v-container>
</template>

<script>
    export default {
        name: "Cart"
    }
</script>

<style scoped>

</style>