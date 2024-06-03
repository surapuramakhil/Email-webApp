<script setup>
import { ref } from 'vue'

const searchString = ref('')

</script>
<template>
    <v-chip class="w-50" center>
        <v-btn icon="mdi-magnify"></v-btn>
        <v-text-field v-model="searchString" placeholder="Search" hide-details clearable solo flat dense
            class="flex-grow-1 mx-2 w-50" />
        <v-btn icon="mdi-tune"></v-btn>
    </v-chip>
</template>