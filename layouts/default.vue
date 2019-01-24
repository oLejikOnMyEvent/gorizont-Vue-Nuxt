<template>
  <v-app light>
    <v-toolbar>
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title>АГЕНТСТВО НЕДВИЖИМОСТИ ГОРИЗОНТ</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat>
          <router-link to="/catalog">Каталог</router-link>
        </v-btn>
        <v-btn flat>
          <router-link to="/about">О НАС</router-link>
        </v-btn>
        <v-btn flat>
          <v-btn flat>
            <router-link to="/">ГЛАВНАЯ</router-link>
          </v-btn>
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>


    <nuxt/>
  </v-app>
</template>


