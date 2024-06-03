<script setup>
import MailSearch from './MailSearch.vue'
</script>
<template>
    <v-app-bar :elevation="2" rounded>
        <template v-slot:prepend>
            <v-app-bar-nav-icon></v-app-bar-nav-icon>
        </template>

        <v-row>

            <v-col cols="1">
                <v-app-bar-title> <v-btn icon="mdi-email"></v-btn> Email </v-app-bar-title>
            </v-col>

            <div class="d-flex justify-center align-center flex-grow-1">
                <MailSearch></MailSearch>
            </div>

        </v-row>

        <template v-slot:append>
            <v-btn icon="mdi-heart"></v-btn>

            <v-btn icon="mdi-magnify"></v-btn>

            <v-btn icon="mdi-dots-vertical"></v-btn>
        </template>
    </v-app-bar>
</template>